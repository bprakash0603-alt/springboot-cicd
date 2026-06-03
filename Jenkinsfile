pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/bprakash0603-alt/springboot-cicd.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
