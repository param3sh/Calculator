pipeline {
  agent any
  tools {
    maven 'MavenLatest'
  }
  stages {
    stage ('Build') {
      steps {
        sh '''
           echo "PATH = ${PATH}"
           echo "M2_HOME = ${M2_HOME}"
           '''
      }
    }
  }
}
