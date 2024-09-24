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

    stage('install node v10 / shell script') {
      steps {
        sh 'echo "stage 2"'
      }
    }

  }
}