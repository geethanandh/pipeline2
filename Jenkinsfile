pipeline {
  agent { label 'A1' }
  stages {
    stage('Example') {
container(A1) {
         steps {
           sh 'npm -v'
         }
      }
    }
  }
}
