pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        sh 'flutter test --coverage test/*'
      }
    }

  }
}