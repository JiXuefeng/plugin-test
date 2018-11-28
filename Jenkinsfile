pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bash './tools/build.sh'
      }
    }
    stage('Test') {
      steps {
        bash './tools/test.sh'
      }
    }
  }
}
