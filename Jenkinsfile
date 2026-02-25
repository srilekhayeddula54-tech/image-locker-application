pipeline {
  agent any

  stages {
    stage('Run Docker App') {
      steps {
        sh 'docker compose down || true'
        sh 'docker compose up -d --build'
      }
    }
  }
}