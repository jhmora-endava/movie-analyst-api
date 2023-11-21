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
    }
}