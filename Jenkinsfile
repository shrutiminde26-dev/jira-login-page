pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git branch: 'SCRUM-5-login-page',
                url: 'https://github.com/shrutiminde26-dev/jira-login-page.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Project'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Tests'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Application'
            }
        }
    }
}