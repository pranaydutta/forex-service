pipeline {
  agent any
  tools {
        maven 'Maven 3.3.9'
       // jdk 'jdk8'
    }
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
