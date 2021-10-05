pipeline {
  agent {
    any {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('primer') {
      steps {
        echo 'hola mundo'
        sh '/usr/bin/npm install'
      }
    }

  }
}