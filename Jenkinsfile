pipeline {
    agent {label 'Java1' }
    stages {
        
        stage('compile') {
            agent {label 'Java1' }
            steps {
                 sh "javac hello.java"
            }
            
        }
        stage('run') {
            agent {label 'Java1' }
            steps {
                sh "java HelloWorld"
            }
        }
    }

       
}
