pipeline {
    agent {
        docker {
            image 'hashicorp/terraform:latest'
        }
    }
    stages {
        stage('Build Application') { 
            steps {
                echo '=== Building Petclinic Application ==='
                sh 'ls -al'
                sh 'whoami'
            }
        }
    }
}
