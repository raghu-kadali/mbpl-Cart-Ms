pipeline {
    agent any 
    environment {
        envi ='pre-prod'
    }
    stages {
        stage('pre') {
            when {
                environment name: 'envi', value: 'pre-prod'
            }
            steps {
                echo print when its is succsful
            }
        }
    }
}
