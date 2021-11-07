pipeline {
    agent any;

    options {
        buildDiscarder(logRotator(numToKeepStr: '2')) 
    }

    stages {
        stage('Git Checkout') {
            steps {
                sh 'echo hell workd'
            }
        }

         stage('Steps2') {
            steps {
                sh 'echo step2'
            }
        }
    }
}
