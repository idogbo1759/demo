pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                python('python'){
                echo 'Building......'
                sh 'python --version'    
            }
            }
        }
        stage('test') {
            steps {
                echo 'Testing......'
            }
        }
         stage('deploy') {
            steps {
                echo 'Deploying......'
            }
        }
  
    }
}
