pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            sh 'echo "Hostname is `hostname`"'
          }
        }

        stage('Parallel_Stage01') {
          steps {
            sh 'echo "Parallel Stage01"'
          }
        }

        stage('Parallel_stage02') {
          steps {
            sh 'echo "Parallel Stage02"'
          }
        }

      }
    }

    stage('Stage2') {
      steps {
        sh 'echo "This is 2nd stage"'
      }
    }

  }
}