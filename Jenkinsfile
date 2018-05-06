pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        powershell(script: 'node {     def status = pwsh(returnStatus: true, script: \'ifconfig\')     if (status == 0) {         // Success!     } }', returnStatus: true, returnStdout: true)
      }
    }
  }
}