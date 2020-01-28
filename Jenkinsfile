pipeline {
    agent any
    stages {
        stage('compile') {
            parallel{
                stage('hello & hi Compile'){
                steps {
                     sh "javac hello.java"
                }
                steps{
                     sh "javac hi.java"       
                 }
               }
             }
                
        }
        stage('run') {
            parallel{
              stage('hi & hello run')
                steps {
                    sh "java HelloWorld"
                 }
                steps {
                    sh "java hi"
                  }
               }
        }
        
    }

       
}
