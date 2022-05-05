pipeline 
{
agent any
  stages 
  {
    
    
    stage ('Build')
    {
      steps {
      sh 'yum install nodejs'
      sh 'npm install'    
      }
   }
    stage ('Deploy')
    {
      steps {
        sh 'npm run start:dev'
      }
   }
  
  
  
  
  
  }

}
