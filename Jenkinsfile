pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        mvnHome = tool 'MavenLatest'
        $mvnHome\bin\mvn compile
      }
    }
  }
}
