 pipeline {
    agent any
    environment {
        DEPLOY_ TO = 'production'
        production = "good"
    }
    stages {
        stage('deployment') {
            when {
                environment name: 'DEPLOY_TO', value: 'production'
                environment name: "production", value: "god"
            }
            steps {
                echo "deployimg the production"
                echo "if gd you can go"
            }
        }
    }
 }
