pipeline {
  agent {
    kubernetes {
      cloud 'kubernetes'
      namespace 'kubernetes'
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
