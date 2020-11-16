pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

    stage('test') {
      steps {
        echo 'this is test'
      }
    }

    stage('deliver') {
      steps {
        echo 'this is a deliver'
      }
    }

  }
}