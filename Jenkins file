pipeline {
    agent any
    stages {
        stage('Checkout') {
            
        }
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Run') {
            steps {
                echo 'Spring Boot app build completed!'
            }
        }
    }
}
