pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Build') {
            steps {
                sh "pwd"
                sh ls "./target"
            }
        }
        stage('Test') {
            steps {
                echo 'Testingtest..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}