pipeline {
    agent {
        docker {
           image 'node:16-alpine'
           args '-u root:root'
       }
    }
    stages {
        stage('Test') {
          steps {
            sh 'node --version'
          }
        }
    }
}