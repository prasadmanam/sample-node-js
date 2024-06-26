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
        sh 'npm install pm2-g'
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

  }
}
