pipeline {
  agent any
  stages {
    stage ('version') {
      steps {
        sh 'python --version'
      }
    }
    stage ('p1') {
      steps {
        sh 'python p1.py'
      }
    }
  }
}
