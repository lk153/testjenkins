pipeline {
    agent { docker { image 'golang:1.17.5-alpine' } }
    environment {
        BRANCH_NAME = 'main'
    }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
