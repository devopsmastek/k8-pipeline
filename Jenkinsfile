pipeline
{
node 
{ 
stage('scm checkout') { 
      def branch = env.BRANCH_NAME
      sh 'git clone -b $branch https://github.com/devopsmastek/k8-pipeline.git'
      sh 'ls'         
   }
 }
}
