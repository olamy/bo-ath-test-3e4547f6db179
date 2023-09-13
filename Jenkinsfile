pipeline {
  agent any
  stages {
    stage('Top Level Parallel Wrapper Stag') {
      parallel {
        stage('Parallel-1') {
          steps {
            sh 'whoami'
          }
        }

        stage('Parallel-2') {
          steps {
            sh 'whoami'
          }
        }

        stage('Parallel-3') {
          steps {
            sh 'whoamie'
          }
        }

      }
    }

  }
}