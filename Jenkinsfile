pipeline {
    agent any

    stages {

        stage('Pull from Git') {
            steps {
                git 'https://github.com/Priyanshu0423/I034_Lab8-Demo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
                sh 'echo Build stage completed'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'echo Test stage completed'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
                sh 'echo Deploy stage completed'
            }
        }

    }
}
