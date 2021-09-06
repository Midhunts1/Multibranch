pipeline {
    agent {
        node {
            label 'Dev'
        }
    }
    stages {
        stage('checkout'){
            steps{
               git 'https://github.com/devopscube/multibranch-pipeline-demo.git'
            }
        }
        stage('Hello') {
            steps {
                echo 'My Dev Project'
            }
        }
    }
}
