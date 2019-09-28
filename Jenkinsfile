
node 
{ 

      stage('Check out code'){
echo "My branch is: ${env.BRANCH_NAME}"
      }
stage('scm checkout') { 
      
       git 'https://github.com/devopsmastek/k8-pipeline.git'
       sh 'ls'         
   }
 }

