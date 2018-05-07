pipeline {
  agent any
  stages {
    stage('Hello World Terminal') {
      steps {
        sh '''#!/bin/sh
open -a /Applications/Utilities/Terminal.app
osascript << END
tell application "Terminal"
echo hello
pause 10
end tell
END'''
      }
    }
  }
}