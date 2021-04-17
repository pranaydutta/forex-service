pipeline {
  agent any
  
  stages {
  stage('Build') {
      steps {
        script {
         sh "mvn -B install"
        }
      }
    }
  stage('Initialize') {
      steps {
        script {
         sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                '''
        }
      }
    }
  }
}
