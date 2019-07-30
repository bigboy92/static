pipeline {
    agent any
    stages {
        stage('Upload to AWS') {
            steps{
                withAWS(region:'eu-east-1', credentials:'nameOfSystemCredentials') {
                    sh 'echo "uploaded files to s3"'
                }
            }
        }
    }
}
