pipeline {
agent any 
  stages{
   stage('Install PM2'){
       steps{
         sh 'sudo npm install -g pm2'
       }
     }
    stage('Build'){
      steps{
        sh 'sudo npm install'
      }
    }
    stage('Deploy'){
      steps{
        sh '''
        echo hello world
        sudo pm2 stop all
        sudo pm2 start bin/www
        '''
      }
    }
  }
}
