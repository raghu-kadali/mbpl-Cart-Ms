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
                anyOf {
                      branch 'production'
                environment name: 'DEPLOY_TO', value: 'productioneeeee'
                }
              
            }
            steps {
                echo "deploying to production environment"
            }
        }
    }
}
