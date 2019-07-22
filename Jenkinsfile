pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'hello'
      }
    }
    stage('') {
      steps {
        sh ' svn checkout https://192.168.88.31/svn/opac/trunk/indexer --username=jenkins --password=libsys'
      }
    }
  }
}