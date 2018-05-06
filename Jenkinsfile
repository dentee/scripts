pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        powershell(script: 'node {     def msg = pwsh(returnStdout: true, script: \'Write-Output "PowerShell is mighty!"\')     println msg }', returnStatus: true, returnStdout: true)
      }
    }
  }
}