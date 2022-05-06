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
        echo 'Hi world'
        sh 'noup npm run start:dev&'
      }
   }
  
  
  
  
  
  }

}
