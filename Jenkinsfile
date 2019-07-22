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
        svn 'https://192.168.88.31/svn/opac/trunk/indexer'
      }
    }
  }
}