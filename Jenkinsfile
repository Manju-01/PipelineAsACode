pipeline {
    agent {node {label 'Java1'} && node {label 'Java'} }
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
