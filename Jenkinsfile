pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hello There!!'
          }
        }

        stage('') {
          steps {
            sh '''date


ls'''
          }
        }

      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh 'pwd'
          }
        }

        stage('') {
          steps {
            echo 'My first'
          }
        }

      }
    }

  }
}