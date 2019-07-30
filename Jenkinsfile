pipeline {
    agent any
    stages {
        stage('Upload to AWS') {
            withAWS(region:'eu-east-1', credentials:'nameOfSystemCredentials') {
                sh 'echo "Uploaded filt to s3"'
            }
        }
    }
}
