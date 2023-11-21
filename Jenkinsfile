pipeline {
    agent any
    stages {
        stage ('Build'){
            steps {
                echo 'Building API'
                sh 'npm build'
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