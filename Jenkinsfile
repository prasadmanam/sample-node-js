pipeline {
  agent any
  stages{
    stage('First Stage'){
      steps{
        sh 'sudo yum install git'
      }
    }
    stage('Second Stage'){
      steps{
        sh 'sudo yum install Node.js'
      }
    }
    stage('Third stage Stage'){
      steps{
        sh 'sudo npm install pm2-g'
      }
    }

        stage('Fourth Stage'){
          steps{
            sh 'npm run start:dev'
          }
        }
    
           stage('Fifth Stage'){
          steps{
            sh 'cd/sample-node-js/path/bin/www' 
          }
           }      
      }
    }


