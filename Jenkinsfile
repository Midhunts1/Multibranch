pipeline {
    agent {
        node {
            label 'master'
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
                echo 'Hello World'
            }
        }
    }
}
