pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
            }
        }
     stage('test') {
            steps {
                echo 'Building...'
                sh 'df -h'
            }
        }
    }
}
