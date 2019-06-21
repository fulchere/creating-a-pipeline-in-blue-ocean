pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '''-p 3000:3000
-u 0:0'''
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
<<<<<<< HEAD
}
=======
  environment {
    HOME = '\'.\''
  }
}
>>>>>>> b3ea2a63aaa48c252df5accc99e37f07f27cbd64
