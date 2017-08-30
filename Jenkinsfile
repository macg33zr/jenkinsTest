pipeline {
  agent {
    node {
      label 'DOCKER_SLAVE'
    }
    
  }
  stages {
    stage('Foo') {
      steps {
        sh 'echo "Hello World!"'
      }
    }
    stage('Bar') {
      steps {
        echo 'Bah!'
      }
    }
  }
  environment {
    test = 'foo'
  }
}