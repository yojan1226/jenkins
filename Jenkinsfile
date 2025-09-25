pipeline {
    agent {
        docker {
            image 'node:16-alpine'
            args '-v C:/ProgramData/Jenkins/.jenkins/workspace/sample_docker_pipeline:/workspace -w /workspace'
        }
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Test') {
            steps {
                sh 'pwd'
                sh 'node --version'
            }
        }
    }
}


