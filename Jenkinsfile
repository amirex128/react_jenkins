pipeline {
  agent {
    docker {
      image 'node:14.18'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'node --version'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "amirex"'
      }
    }

  }
}