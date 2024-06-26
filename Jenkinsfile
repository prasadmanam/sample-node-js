pipeline {
  agent any
  stages{
    stage('First Stage'){
      steps{
        sh 'Install Node.js'
      }
    }
    stage('Second Stage'){
      steps{
        sh 'npm install'
      }
    }

    stage('Third Stage'){
      steps{
        sh 'pm2-g'
        stage('Fourth Stage'){
          steps{
            sh 'Start Node.js'
           stage('Fifth Stage'){
          steps{
            sh 'cd /path/bin/www' 
          }
           }
          }
        }
            
      }
    }

  }
}
