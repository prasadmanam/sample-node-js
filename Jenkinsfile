pipeline {
  agent any
  stages{
    stage('First Stage'){
      steps{
        sh 'sudo yum install git -y'
      }
    }
    
    stage('Third stage Stage'){
      steps{
        sh 'sudo npm install pm2 -g'
      }
    }

        stage('Fourth Stage'){
          steps{
            sh 'sudo npm install'
          }
        }
    
           stage('Fifth Stage'){
          steps{
          
           sh 'sudo pm2 start'

            stage ('Build Dockerimage'){
              sh 'docker build-t tag jendocimage .
            }
            
          }
           }      
      }
    }


