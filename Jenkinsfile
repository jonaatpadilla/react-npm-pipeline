pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'hola mundo'
        sh '/usr/bin/npm install'
      }
    }

  }
  environment {
    CI = 'true'
  }
}