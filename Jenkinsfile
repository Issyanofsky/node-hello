pipeline {
  agent {
    node {
      label 'jenkinks-docker-slave'
    }

  }
  stages {
    stage('echeckout-code') {
      steps {
        sh 'echo "hello world"'
      }
    }

    stage('Build') {
      steps {
        sh 'echo "stage 2"'
      }
    }

  }
}