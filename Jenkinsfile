pipeline {
  agent any
  stages {
    stage('mvn version') {
      parallel {
        stage('mvn version') {
          steps {
            sh 'mvn --version'
          }
        }

        stage('maven run') {
          steps {
            sh 'mvn clean test'
          }
        }

      }
    }

  }
}