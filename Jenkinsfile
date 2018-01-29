pipeline {
    agent any

    stages {
        stage('Build') {
            agent {
                label 'docker'
            }
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            agent {
                label 'maven-jdk-8'
            }
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
