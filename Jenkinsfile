pipeline {
    agent {name 'slave01','SandySlave'}
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
