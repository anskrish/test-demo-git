pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello Worldds!"
            }
        }
     stage('test') {
            steps {
                echo 'Building...'
                sh 'df -h'
            }
        }
     stage('deploy') {
            steps {
                echo 'Building...'
                sh 'mkdir /tmp/test1'
                sh 'free -m'
            }
        }
    }
}
