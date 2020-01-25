pipeline {
    agent {label 'Java1' }
    stages {
        
        stage('compile') {
            steps {
                 sh "javac hello.java"
            }
        }
        stage('run') {
            steps {
                sh "java HelloWorld"
            }
        }
        agent {label 'java'}
        stage('compile') {
            steps {
                 sh "javac hello.java"
            }
        }
        agent {label 'java'}
        stage('run') {
            steps {
                sh "java HelloWorld"
            }
        }
    }

       
}
