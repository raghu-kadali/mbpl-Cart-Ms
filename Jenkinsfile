pipeline {
    agent any 
    environment {
        DEPLOY_TO = 'production'
    }
    stages {
        stage('deploy to dev') {
            steps {
                echo "deploy dev envi"
            }
        }
        stage('prod-deploy') {
            when {
                allOf {
                      branch 'production'
                environment name: 'DEPLOY_TO', value: 'Production'
                }
              
            }
            steps {
                echo "deploying to production environment"
            }
        }
    }
}
