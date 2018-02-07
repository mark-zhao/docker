pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh 'echo 0'
          }
        }
        stage('') {
          steps {
            sh 'echo 0'
          }
        }
      }
    }
    stage('') {
      steps {
        sh 'echo 1'
      }
    }
  }
}