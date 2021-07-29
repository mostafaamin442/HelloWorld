pipeline {
    agent any

    stages {
        stage('SCM checkout') {
            steps {
                echo 'getting from github'
                echo 'checout completed'
                echo " change request"
            }
        }
        stage('Build') {
            steps {
                echo 'Build completed'
            }
        }
        stage('Test') {
            steps {
                 echo 'test completed'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy completed'
            }
        }
    }
}
