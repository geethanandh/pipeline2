pipeline {
   agent {
        docker { image 'node:7-alpine' }
    }

  stages {
    stage('Poll') {
      steps {
        git(poll: true, url: 'https://github.com/geethanandh/pipeline2.git')
        echo 'Cool'
      }
    }
	
	 stage ('Checkout Code') {
      steps {
        checkout scm
      }
    }
    stage ('Verify Tools'){
      steps {
        parallel  sh "npm -v" 
		}
      }
    }
}