pipeline{
    agent any
    stages{
        stage('1-first stage'){
            steps{
                sh ''checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-id', url: 'https://github.com/NanjeD/testing.git']]])
            }
        }
        stage('2-system update'){
            steps{
                sh 'free -m'
            }
        }
    }
}