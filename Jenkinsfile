pipeline{
    agent any
    stages{
        stage('1-git clone'){
            steps{
                sh 'checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/NanjeD/testing.git']]])'
            }
       
