pipeline
{
agent any
stages
{ 
 
 stage('scm checkout')
 { steps { sh 'echo stage-1'} }


 stage ('please execute parallel stages')
  {
  
   parallel
   {
  
    stage ('stage-parallel-1') 
     { steps  { sh 'echo stage-parallel-1' }
     } 

    stage ('stage-parallel-2') 
     { steps  { sh 'echo stage-parallel-2' }
     } 
    
    stage ('stage-parallel-3') 
     { steps  { sh 'echo stage-parallel-3' }
     } 
   }
   }

}
}
