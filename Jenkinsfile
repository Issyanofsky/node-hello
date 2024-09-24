pipeline {
  agent {
    node {
      label 'jenkinks-docker-slave'
    }

  }
  stages {
    stage('error') {
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