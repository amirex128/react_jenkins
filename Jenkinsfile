pipeline {
  agent {
    docker {
      image 'node:12'
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