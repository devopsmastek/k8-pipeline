
node 
{ 
 stage('Check out code'){
echo "My branch is: ${env.BRANCH_NAME}"
      }
     
   
stage('scm checkout') { 
       def master='master'
       def dev='dev'
       git 'https://github.com/devopsmastek/k8-pipeline.git'      
       sh 'ls'         
   }
 stage('deploy to production') {

  if ( ${master} == ${env.BRANCH_NAME} ) {
            
             sh 'cp README.md /app/README.md'
            }
      
      }
     
     
 }

