pipeline {
    agent {
        label 'AGENT-1'
    }
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'MINUTES')
    }
    stages{
        stage('Build'){
            steps{
                sh 'echo this is Build'
            }
        }
        stage('Test'){
            steps{
                sh 'echo this is a Test'
                sh 'sleep 10'
            }
        }
        stage('Deploy'){
            steps{

                sh 'echo this is Deploy'
            }
        }
    }
}