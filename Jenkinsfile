pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "hello world"'
        sleep 5
      }
    }

  }
  environment {
    environment = 'dev'
  }
}