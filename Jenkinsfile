pipeline {
  agent any
  stages {
  stage('Stage 1') {
      steps {
        script {
          mvn clean install
        }
      }
    }
  stage('Stage 2') {
      steps {
        script {
          echo 'Stage 2'
        }
      }
    }
  }
}