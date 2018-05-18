pipeline {
  agent any
  stages {
    stage('Deploy') {
      parallel {
        stage('Deploy') {
          steps {
            echo 'Let\'s deploy'
          }
        }
        stage('error') {
          steps {
            sh 'docker-compose -v'
          }
        }
      }
    }
  }
}