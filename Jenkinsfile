pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'I am in dev'
                sh 'git --version'
            }
        }
    stage('docker test') {
            steps {
                echo 'I am in test'
                sh 'docker --version'
                sh 'sudo docker pull nginx:latest'
            }
        }
    }
}
