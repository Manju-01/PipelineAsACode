pipeline {
    agent any
    stages {
        stage('compile') {
            parallel{
               stage('hello Compile'){
                    steps {
                         sh "javac hello.java"
                    }
                }
                stage('hi Compile'){
                    steps{
                         sh "javac hi.java"       
                     }
                }
               
            }
          }
        stage('run') {
            parallel{
                stage('hello run') {
                    steps {
                        sh "java HelloWorld"
                     }
              }
                stage('hi run'){
                    steps {
                        sh "java hi"
                  }
              }
        }
        
    }
    }
       
}
