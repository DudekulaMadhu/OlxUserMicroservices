pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/mohammadazeez963/javaProject'
            }
        }
        stage('compile') {
            steps {
                echo 'compile'
            }
        }
        stage('running') {
            steps {
                echo 'running'
            }
        }
    }
}
