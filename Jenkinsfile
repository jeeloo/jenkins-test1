pipeline {
    agent any

    stages {
        stage('Build') {
            agent {
                label 'docker'
            }
            steps {
                echo 'Building..'
                sh 'env'
            }
        }
        stage('Test') {
            agent {
                label 'maven-jdk-8'
            }
            steps {
                echo 'Testing..'
                sh 'env'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh 'env'
            }
        }
    }
}
