pipeline {
  agent any
  stages {
    stage('mvn version') {
      parallel {
        stage('mvn version') {
          steps {
            bat 'mvn --version'
          }
        }

        stage('maven run') {
          steps {
            bat 'mvn clean test'
          }
        }

      }
    }

  }
}