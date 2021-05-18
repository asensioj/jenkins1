pipeline {
    agent any
    
    stages {
        stage('Stage 1') {
            steps {
                sh 'date'
            }   
        }
        stage('Stage 2') {
            steps {
                sh 'wc -l /etc/passwd'
            }   
        }
    }
}
