pipeline {
    agent any
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
