pipeline {
    agent any

    stages {
        stage('Build') {
            agent {
                label 'docker'
            }
            steps {
                echo 'Building..'
                env
            }
        }
        stage('Test') {
            agent {
                label 'maven-jdk-8'
            }
            steps {
                echo 'Testing..'
                env
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                env
            }
        }
    }
}
