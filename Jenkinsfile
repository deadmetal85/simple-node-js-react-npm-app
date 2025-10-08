pipeline {
    agent any
    tools {
        nodejs "NodeJS LTS"
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}