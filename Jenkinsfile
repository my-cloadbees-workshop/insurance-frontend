pipeline {
  agent none
  stages {
    stage('Say Hello') {
      agent {label 'nodejs-app'}
      steps {
        echo 'Hello World!'   
        sh 'java -version'
        container('nodejs') {
          echo 'Hello World!'   
          sh 'node --version'
        }
      }
    }
  }
}
