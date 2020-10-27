pipeline {
  agent any
  tools {
    maven 'M2-HOME'
  }
  stages {
    stage('compile stage') {
      steps {
        sh script: 'mvn compile'
      }
    }
    stage('package stage') {
      steps {
        sh script: 'mvn package'
      }
    }
  }
}
