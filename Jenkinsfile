pipeline {
    agent any
       triggers {
        pollSCM "* * * * *"
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
