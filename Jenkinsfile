pipeline {
    agent any
    stages {
        stage ('Build'){
            steps {
                echo 'Building API'
                sh 'npm install'
            }
        }
        stage ('Test'){
            steps{
                echo 'Running tests'
                sh 'npm run test'
            }
        }
        stage ('Build and push Docker image'){
            steps{
                sh 'docker build -t jhmora/ui .'
            }
        }
    }
}