pipeline {
  agent none
  stages {
    stage('Say Hello') {
      agent nodejs-app
      steps {
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}
