pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Say Hello') {
            steps {
                sh 'echo Hello, Jenkins!'
            }
        }
    }
}
