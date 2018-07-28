pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'echo "%NAME%'
      }
    }
    stage('test') {
      steps {
        bat 'echo "hello"'
      }
    }
  }
  environment {
    NAME = 'VARSHA'
  }
}