pipeline {
  agent any
  stages {
    stage('') {
      steps {
        powershell(script: 'node {     def status = powershell(returnStatus: true, script: \'ipconfig\')     if (status == 0) {         // Success!     } }', returnStatus: true)
      }
    }
  }
}