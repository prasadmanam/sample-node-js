  pipeline {
    agent any

stages {
  
    stage('Build docker image') {
            steps {  
            
                sh 'sudo docker build -t prasad/sample-node-js:$BUILD_NUMBER .'
            }

      
      
            }
  stage('stop conatiner manam'){
  steps {
  sh 'sudo docker stop manam'
    sh 'sudo rm manam'
    sh 'sudo docker run -itd -p 3000:3000 --name manam prasad/sample-node-js:$BUILD_NUMBER'
  }  }
  
      }
  }    
        
        

