pipeline{
    agent any
    stages{
      stage('checkout') {
      steps {
         sh 'git 'https://github.com/jagadeeshdevops/sample_pipe_line.git''
           }
      }
       stage('build') {
       steps{
          sh 'mvn install'
            }
       }
   }
} 
