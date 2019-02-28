pipeline {
   agent {
        node 'nodejsanandh'
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
         sh "npm -v" 
		}
      }
    }
}