pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Test Message'
      }
    }
    stage('Second Test') {
      parallel {
        stage('Second Test') {
          steps {
            echo 'Hi friends'
          }
        }
        stage('Par Test') {
          steps {
            echo 'Other'
          }
        }
      }
    }
  }
}