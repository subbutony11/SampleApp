pipeline {
  agent any { 
   stages {
        stage('Build') {
          script {
          steps {
            sh 'npm install'
          }
        }
      }
   }
  stage('Test') {
    steps {
      script {
        sh './jenkins/scripts/test.sh'
      }
    }
  }
}
            
