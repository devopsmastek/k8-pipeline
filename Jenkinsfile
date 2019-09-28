
node 
{ 
      
stage ('branch') {
  sh "echo '${env.GIT_BRANCH}'"
}

stage('scm checkout') { 
      
       git 'https://github.com/devopsmastek/k8-pipeline.git'
       sh 'ls'         
   }
 }

