pipeline {
    agent any
    //global declaration

    environment{
        githubCredintials = Credintals('cec5d559-77d3-4da6-856c-a69d5ebc5ca0')
    }
    //stages will go under
    stages {
        
         stage('Clone sources') {
            git 'https://github.com/mohannedsa/jenkinsPipeline.git'
        
        }


        stage('build') {
            steps {
                echo 'Hello World'
                
                
                //sh "${githubCredintials}"
            }
        }
    }
}
