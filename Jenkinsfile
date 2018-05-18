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
        stage('') {
          steps {
            sh 'docker-compose up -d'
          }
        }
      }
    }
  }
}