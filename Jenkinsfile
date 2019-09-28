
node 
{ 
      
stage ('branch') {
  def branch =${env.GIT_BRANCH}
  sh "echo '$branch'"
}

stage('scm checkout') { 
      
       git 'https://github.com/devopsmastek/k8-pipeline.git'
       sh 'ls'         
   }
 }

