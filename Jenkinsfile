pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // This checks out the source code from the configured SCM
                checkout scm
            }
        }
        stage('Test SCM') {
            steps {
                echo 'SCM checkout successful!'
            }
        }
    }
}
