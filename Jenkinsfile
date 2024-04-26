pipeline {
    agent {
        docker { image 'node:21-slim' }
    }
    stages {
        stage('build') {
            steps {
                echo 'Building......'
                sh 'node --version'
            }
        }
    }
}
