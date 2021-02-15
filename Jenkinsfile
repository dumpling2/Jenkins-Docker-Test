pipeline {
    agent { Dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'npx mocha ./tests/systemtest.js'
            }
        }
    }
}