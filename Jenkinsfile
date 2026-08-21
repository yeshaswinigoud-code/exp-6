pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from GitHub...'
            }
        }

        stage('Run Python') {
            steps {
                sh 'python3 hello.py'
            }
        }

        stage('Build Success') {
            steps {
                echo 'Jenkins build completed successfully!'
            }
        }
    }
}
