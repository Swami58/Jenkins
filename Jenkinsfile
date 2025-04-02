pipeline {
    agent {
        label 'Agent-1'
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
            }
        }
        stage('Deploy'){
            steps{

                sh 'echo this is Deploy'
            }
        }
    }
}