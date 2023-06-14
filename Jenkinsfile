pipeline 
{
agent any
  stages 
  {    
    
    stage ('Build')
    {
      steps {
      sh 'npm install'    
      }
   }
    stage ('Deploy')
    {
      steps {
        script {
       withEnv(['JENKINS_NODE_COOKIE=dontkill']) {
          echo 'Hi world'
        sh 'nohup npm run start:dev&'
      }
        }
      }
   }
  
  
  
  
  
  }

}
