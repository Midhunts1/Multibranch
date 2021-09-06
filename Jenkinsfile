pipeline {
    agent any
    tools {
        terraform 'Terraform'
    }
    stages {
        stage('checkout'){
            steps{
               git 'https://github.com/devopscube/multibranch-pipeline-demo.git'
            }
        }
        stage('Terraform init'){
            steps{
                bat returnStatus: true, script: echo "Running Unit Tests"
            }
        }
    }
}
