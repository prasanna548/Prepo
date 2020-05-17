pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'echo \'tesy\''
          }
        }

        stage('error') {
          steps {
            sh 'echo \'sahj\''
          }
        }

      }
    }

    stage('run') {
      steps {
        sh 'echo \'run\''
      }
    }

  }
}