pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-u 0:0'
    }

  }

    environment {
    }


  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}
