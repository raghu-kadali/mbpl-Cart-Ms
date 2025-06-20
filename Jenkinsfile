pipeline {
    agent any
    environment {
        DEPLOY_TO = 'production'
    }
    stages {
        stage('production') {
            when {
                equals expected: 'prod' actual:"${DEPLOY_TO}"
            }
        }
    }
}
