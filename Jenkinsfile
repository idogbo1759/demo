pipeline {
    agent any
    stages {      
        stage('hello') {
            when {
                branch 'main'
            }
            steps {
               echo 'building..........'
                sh './hello.sh'
            }
        }
    }
}
