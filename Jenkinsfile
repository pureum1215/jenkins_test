pipeline {
    agent any
    stages {
        stage('Prepare'){
            steps {
                git credentialsId: 'pureum1215',
                    branch: 'main',
                    url: 'https://github.com/pureum1215/jenkins_test.git'
            }
        }
        stage('test') {
            steps {
                echo 'test stage'
            }
        }
        stage('build') {
            steps {
                echo 'build stage'
            }
        }
        stage('docker build') {
            steps {
                echo 'docker build stage'
            }
        }
    }
}