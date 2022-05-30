pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'echo "Hostname is `hostname`"'
      }
    }

    stage('Stage2') {
      steps {
        sh 'echo "This is 2nd stage"'
      }
    }

  }
}