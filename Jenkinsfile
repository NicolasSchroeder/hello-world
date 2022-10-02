pipeline {
  agent {
    kubernetes {
      cloud 'kubernetes'
      namespace 'jenkins'
    }
  }
  stages {
    stage('hello world') {
      steps {
        echo 'hello world'
      }
    }

  }
}
