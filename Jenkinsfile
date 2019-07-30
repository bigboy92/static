pipeline {
    agent any
    stages {
        stage('Upload to AWS') {
            steps{
                withAWS(region:'eu-east-1', credentials:'aws-static') {
                    sh 'echo "uploaded files to s3"'
                }
            }
        }
    }
}
