pipeline {
  agent {
    node {
      label 'jenkinks-docker-slave'
    }

  }
  stages {
    stage('checkout-code') {
      steps {
        sh 'echo "Hello World!!"'
      }
    }

    stage('test') {
      steps {
        sh 'echo "Test 124"'
      }
    }

  }
}