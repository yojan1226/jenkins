pipeline {
  agent {
    docker {
      image 'node:16-alpine'
    }
  }
  stages {
    stage('Test') {
      steps {
        sh 'pwd'
        sh 'node --version'
      }
    }
  }
}


