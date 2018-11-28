pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh ' tools/build.sh'
      }
    }
    stage('Test') {
      steps {
        sh ' tools/test.sh'
      }
    }
  }
}
