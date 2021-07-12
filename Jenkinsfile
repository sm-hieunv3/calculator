pipeline {
    agent {
        docker {
            image 'hashicorp/terraform:latest'
            label 'any'
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
