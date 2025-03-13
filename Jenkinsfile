pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                sh 'sleep 30'
            }
        }
        stage('Build') {
            steps {
                sh 'sleep 50'
            }
        }
        stage('Sonar') {
            steps {
                sh 'sleep 20'
            }
        }
        stage('Deployment') {
            steps {
                sh 'sleep 10'
            }
        }
        stage('Security Scans') {
            steps {
                sh 'sleep 30'
            }
        }
        stage('Performance Scans') {
            steps {
                sh 'sleep 20'
            }
        }
        stage('Functional testing') {
            steps {
                sh 'sleep 10'
            }
        }
    }
}
