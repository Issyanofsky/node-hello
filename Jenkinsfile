pipeline {
  agent {
    node {
      label 'jenkinks-docker-slave'
    }

  }
  stages {
    stage('checkout-code') {
      steps {
        git(url: 'https://github.com/Issyanofsky/node-hello.git', branch: 'master', changelog: true, poll: true)
      }
    }

    stage('build') {
      steps {
        sh 'echo "Buikd"'
      }
    }

  }
}