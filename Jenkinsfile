pipeline {
    agent any
    
    environment {
        FICHERO = '/etc/passwd'
    }
    
    stages {
        stage('Stage 1') {
            steps {
                sh 'date'
            }   
        }
        stage('Stage 2') {
            steps {
                sh 'wc -l ${FICHERO}'
            }   
        }
    }
}
