pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Python is running in Jenkins!'
                sh 'python --version'
                sh 'python pipeline.py'
                echo 'Checks github every minute!'

            }
        }
    }
}
