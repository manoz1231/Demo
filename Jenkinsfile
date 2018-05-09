pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hi this is test'
      }
    }
    stage('test') {
      steps {
        sh 'echo "test is sucesful"'
      }
    }
    stage('finish') {
      steps {
        sh 'echo "end step"'
      }
    }
  }
}