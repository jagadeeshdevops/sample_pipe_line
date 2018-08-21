pipeline{
    agent any
    stages{
      stage('checkout') {
      steps {
         checkout scm
                     }
      }
        stage ('Build') {
            steps {
                sh 'mvn -Dmaven.test.failure.ignore=true install' 
        }
           }
       
   }
} 
