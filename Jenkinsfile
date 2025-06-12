pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }

        stage('Run Python Script') {
            steps {
                bat 'python hello_world_jenkins.py'
            }
        }
    }
}
