pipeline {
    agent {
        docker { 
            image 'node:16-alpine'
            args '-v C:/ProgramData/Jenkins/.jenkins/workspace/docker_pipeline_demo:/workspace -w /workspace'
        }
    }
    stages {
        stage('test') {
            steps {
                sh 'pwd'
                sh 'node --version'
            }
        }
    }
}

