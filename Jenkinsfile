pipeline {
    agent any 
    environment {
        envi ='pre-prod'
    }
    stages {
        stage('pre-prod') {
            when {
                environment name: 'envi', value: 'pre-prod'
            }
        }
    }
}

