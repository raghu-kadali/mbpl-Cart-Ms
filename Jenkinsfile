pipeline {
    agent any 
    environment {
        name = "Chubby"
        course = "gcp-devops"
    }
    stages {
        stage('Build') {
            environment {
                cloud = "amazon"
            }
            steps {
                echo "my name is ${name}"
                echo "you are learning ${course}"
                echo "one of the cloud provider is ${cloud}"
            }
        }
    }
    
}
