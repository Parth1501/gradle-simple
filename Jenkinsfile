pipeline {
  docker {
    image 'gradle:4.7.0-jdk8-alpine'
    
  }
  stages {
    stage('Build') {

      steps {
        sh './gradlew assemble'
      }
    }

  }
}
