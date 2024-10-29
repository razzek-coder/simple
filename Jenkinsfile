pipeline {
  agent none

  stages {
    stage ('jdk 8') {
      agent { label 'jdk8' }
      steps {
        sh 'java -version'
      }
    }
    stage('jdk 21') {
      agent { label 'jdk21' }
      steps {
        sh 'java -version'
      }
    }
  }
}
