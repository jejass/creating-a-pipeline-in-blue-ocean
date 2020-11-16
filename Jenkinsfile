pipeline {
  agent any
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