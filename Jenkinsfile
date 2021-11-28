pipeline {
    agent any

    stages {
        stage('complie & clean') {
            steps {
                
                sh "mvn clean complie"
            }
        }
        stage('Test') {
            steps {
                sh "mvn test"
            }
        }
        stage('Deploy') {
            steps {
                sh "mvn package"
            }
        }
    }
}

