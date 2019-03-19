node {
   currentBuild.result = "SUCCESS"
   stage('Unit testing') {
      sh 'echo "Unit testing"'
   }
   stage('System tests') {
      sh 'exit 1'
   }
   stage('Deploy to prod') {
      sh 'echo "Deploy to prod"'
   }
}
