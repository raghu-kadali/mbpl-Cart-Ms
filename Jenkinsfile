pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo "build the application"
            }
        }
        stage('code analysis') {
            steps {
                echo "inspect the continuos code quality"
            }
        }
        stage('Docker') {
            steps {
                echo "build the docker image then push into docker registry"
            }
        }
        stage('Deploy to Dev') {
            steps {
                echo "Deploy to dev based on docker image the environment runs in container"
            }
        }
        stage('deploy to test environment') {
            steps {
                echo "deploy and check code fumnctionality Api etc"
            }
        }
        stage('deploy to stage') {
            steps {
                 when {
                branch 'release/*'
            }
              echo "deploy to stage environment"
            }
           
        }
        stage('production') {
            steps {
                echo "go to alive to users"
            }
        }
    }
}
