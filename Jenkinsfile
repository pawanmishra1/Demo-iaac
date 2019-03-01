pipeline {
  agent any
  stages {
    stage('Test ') {
      parallel {
        stage('Test ') {
          steps {
            echo 'Hello'
          }
        }
        stage('Build ') {
          steps {
            echo 'Hello'
          }
        }
      }
    }
    stage('Deploy ') {
      steps {
        echo 'Hello'
      }
    }
    stage('') {
      steps {
        echo 'Hello'
      }
    }
  }
  environment {
    env = 'Dev'
    env1 = 'Prod'
  }
}