pipeline {

    agent any

    environment{
        githubCredintials = credentials('cec5d559-77d3-4da6-856c-a69d5ebc5ca0')
    }
  
    stages {
        stage("user out put") {
        
            steps {
                echo "credi: ${githubCredintials_PSW}  ${githubCredintials_USR}"
            
            }
        }   
           
        stage("clone") {
        
            steps {
                
                echo 'Cloning...'
                git url: "https://github.com/mohannedsa/jenkinsPipeline.git" 
            }
        }  
    }
}                
