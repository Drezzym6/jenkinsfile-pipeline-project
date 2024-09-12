pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Pipeline with Poll SCM by Andre Diya'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
