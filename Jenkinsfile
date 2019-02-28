pipeline {
  agent any
  stages {
    stage('Poll') {
      steps {
        git(poll: true, url: 'https://github.com/geethanandh/pipeline2.git')
        echo 'Cool'
      }
    }
  }
}