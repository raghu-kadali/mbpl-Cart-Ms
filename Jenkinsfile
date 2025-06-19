pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "build the src appplication"
            }
        }
        stage('sonar') {
            steps {
                echo "check the codeqaulity and passes the result throughj qauality gates"
            }
        }
        stage('docker') {
            steps {
                echo "yes you finish the container"
            }
        }
        stage('k8s') {
            steps {
                echo "master and workernode succesfully maintained"
            }
        }
    }
}
