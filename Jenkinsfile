pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '/var/lib/jenkins/workspace/plugin-test_master/tools/build.sh'
      }
    }
    stage('Test') {
      steps {
        sh ' tools/test.sh'
      }
    }
  }
}
