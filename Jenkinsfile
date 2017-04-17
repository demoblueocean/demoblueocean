pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'first step of the pipe'
      }
    }
    stage('Testing') {
      steps {
        sh 'echo PATH = ${PATH}'
      }
    }
  }
}