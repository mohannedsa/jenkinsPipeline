pipeline {
    agent any
    //global declaration

    environment{
        githubCredintials = Credintals('cec5d559-77d3-4da6-856c-a69d5ebc5ca0')
    }
    //stages will go under
    stages {
        stage('build') {
            steps {
                git 'https://github.com/mohannedsa/jenkinsPipeline.git'

                echo 'Hello World'
                
                
                //sh "${githubCredintials}"
            }
        }
    }
}
