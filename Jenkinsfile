pipeline {
    agent any
    stages {
        stage('Build docker image') {
            steps {
                sh 'docker build --no-cache -t test:1 .'
            }
        }
    }
}
