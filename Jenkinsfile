pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sh ./tools/build.sh'
      }
    }
    stage('Test') {
      steps {
        sh 'sh ./tools/test.sh'
      }
    }
  }
}