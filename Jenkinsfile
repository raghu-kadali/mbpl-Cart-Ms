pipeline {
    agent any 
    //global levell acces to each stage
    environment {
        name = "Chubby"
        cloud = "gcp-devops"
    }
        stages {
        stage('Build') {
            // only  this stage level this environmental not assigned to other stages 
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
