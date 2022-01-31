pipeline {
    agent any
    
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
                sh 'python3 manage.py runserver 0.0.0.0:8086 &'
            }
        }
    }
}
