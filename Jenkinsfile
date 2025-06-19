pipeline {
    agent any 
    environment {
        cloud ="amazon"
    }
    stages {
        stage('build') {
            environment {
                cloud = "gcp"
            }
            steps {
                echo "my name is ${cloud}"
            }
        }
    }
}
