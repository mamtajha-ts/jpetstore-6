pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Starting to build'
        sh 'mvn clean install -Dlicense.skip=true'
        echo 'Build Step completed'
      }
    }

  }
}