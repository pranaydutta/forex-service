pipeline {
  agent any
  stages {
  stage('Stage 1') {
      steps {
        script {
         sh "mvn -B install"
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
