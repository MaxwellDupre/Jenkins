pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        fileExists 'Jenkinsfile'
      }
    }

  }
  environment {
    Build = 'server'
  }
}