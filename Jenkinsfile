pipeline {
  agent none
  stages {
    stage('Deploy') {
      steps {
        publishEvent simpleEvent('hello-api-push-event')
      }
    }
  }
}
