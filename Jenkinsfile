pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/gutardivo/jenkins-mock-project.git'
            }
        }
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Run Tests') {
            steps {
                sh 'npm test'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Build step: No real build needed for this project"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying mock application..."'
            }
        }
    }
}

