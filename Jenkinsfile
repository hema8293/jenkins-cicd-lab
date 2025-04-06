pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the HTML app...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running basic tests...'
                sh 'test -f my-html-app/index.html'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying app (simulated)...'
            }
        }
    }
}
