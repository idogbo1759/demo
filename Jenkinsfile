pipeline {
    agent any
    stages {
        stage('full-path') {
            steps {
                cat 'my-dir/output.txt'
            }
        }
        stage('dir') {
            steps {
               dir('my-dir'){
                   cat 'output.txt'
            }
        }
    }
}
