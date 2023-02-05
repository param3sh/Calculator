pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        mvnHome = tool 'MavenLatest'
        mvn compile
      }
    }
  }
}
