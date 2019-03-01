pipeline {
   agent any
tools {
    nodejs 'NodejsAnandh'
  }
  stages {
    
    stage ('Verify Too0ls'){
      steps {
         sh "/home/jenkins/tools/jenkins.plugins.nodejs.tools.NodeJSInstallation/NodejsAnandh/bin/npm -v" 
		}
      }
    }
}