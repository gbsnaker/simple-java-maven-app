pipeline {
  agent {
    docker {
      image 'maven:3.3.3'
    }
    
  }
  stages {
    stage('test') {
      steps {
        sh 'sh \'mvn test\''
      }
    }
  }
}