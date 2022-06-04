pipeline{
    agent any
    stages{
        stage('1-first stage'){
            steps{
                sh 'lscpu'
            }
        }
        stage('2-system update'){
            steps{
                sh 'free -m'
            }
        }
    }
}