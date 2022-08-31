pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               bat 'googlechrome basic.html'
            }
        }
        stage('Test') {
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
