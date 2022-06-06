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
        stage('test report using jacoco') {
            steps {
                echo 'jacoco'
            }
        }
        stage('Building Docker Image') {
            steps {
                echo 'Building Docker Image'
            }
        }
    }
}
