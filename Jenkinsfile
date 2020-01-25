pipeline {
    agent {label 'Java' }
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
    }
       
}
