pipeline {
  agent {
    label 'docker'
  }
  stages {
    stage('Docker node test') {
      agent {
        docker {
          label 'docker'
          image 'node:7-alpine'
          args '-p 3000:3000'
        }

      }
      steps {
        sh 'npm install'
      }
    }

  }
}