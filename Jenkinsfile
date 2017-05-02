pipeline {
  agent any
  stages {
    stage('Demo') {
      steps {
        bat(script: 'dir', returnStatus: true, returnStdout: true)
      }
    }
  }
}