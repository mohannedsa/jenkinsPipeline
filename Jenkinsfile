pipeline {

    agent any

    environment{
        githubCredintials = credentials('cec5d559-77d3-4da6-856c-a69d5ebc5ca0')
    }
    
    stages {
    
        stage("build") {
        
            steps {
                echo 'Cloning...'
                echo "credi: ${githubCredintials}"
                sh "${githubCredintials}"

                git 'https://github.com/mohannedsa/jenkinsPipeline.git'
            }
        }
        
        
        
    }   
}
