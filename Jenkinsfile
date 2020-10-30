pipeline {
  agent any
  
  stages{
    stage('Build docker image') {
      steps {
        sh 'docker -t cyberfrat:$BUILD_NUMBER .'
      }
    }
  }
}
