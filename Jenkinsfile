pipeline {
  agent any
  stages {
    stage('DOCKER LOGIN') {
      steps {
        sh 'docker login -u $DOCKERUSER -p $DOCKERPASS'
        sh 'docker images'
      }
    }

  }
  environment {
    DOCKERUSER = 'umsaldanha'
    DOCKERPASS = '253154Saldanha'
  }
}