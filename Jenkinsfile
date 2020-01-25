pipeline {
    agent none
    stages {
        
        stage('compile') {
            agent {label 'Java'}
            steps {
                 sh "javac hello.java"
            }
            
        }
        stage('run') {
            agent {label 'Java'}
            steps {
                sh "java HelloWorld"
            }
        }
        stage('compile1') {
            agent {label 'Java1'}
            steps {
                 sh "javac hello.java"
            }
            
        }
        stage('run1') {
            agent {label 'Java1'}
            steps {
                sh "java HelloWorld"
            }
        }
    }

       
}
