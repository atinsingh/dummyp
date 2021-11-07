pipeline {
    agent any;

    options {
        buildDiscarder(logRotator(numToKeepStr: '3')) 
    }

    stages {
        stage('Git Checkout') {
            steps {
                sh 'echo hell workd'
            }
        }

         stage('Steps2') {
            steps {
                sh 'step2'
            }
        }
    }
}
