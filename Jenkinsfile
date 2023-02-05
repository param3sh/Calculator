pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        script {
          mvnHome = tool 'MavenLatest'
          mvn compile
        } 
      }
    }
  }
}
