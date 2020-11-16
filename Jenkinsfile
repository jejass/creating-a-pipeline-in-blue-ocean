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
        sh 'echo \'this is build steps\''
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