// pipeline {
    // agent {
    //     // docker { image 'node:20.9.0-alpine3.18' }
    // }
    stages {
        stage('Test') {
            steps {
                echo 'test'
                sh 'node --version'
                sh 'npm ci'
                sh 'npm run test'
            }
        }
    }
// }