pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Cloning code from GitHub...'
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running test cases...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application to test environment...'
            }
        }

        stage('Release') {
            steps {
                echo 'Releasing final build...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully!'
        }
        failure {
            echo 'Pipeline failed — check error logs.'
        }
    }
}
