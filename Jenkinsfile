pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'TODO: build'
                sh './mvnw clean compile -e'
            }
        }
        stage('Test') {
            steps {
                echo 'TODO: test'
                sh './mvnw.cmd clean test -e'
            }
        }
        stage('Package') {
            steps {
                echo 'TODO: package'
                sh './mvnw.cmd clean package -e'           
            }
        }
        stage('Run') {
            steps {
                echo 'TODO: run'
                sh './mvnw.cmd spring-boot:run'            
            }
        }
    }
}
