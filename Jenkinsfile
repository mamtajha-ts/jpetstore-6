pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Starting to build'
        sh '''export MAVEN_HOME=/opt/maven
export PATH=$PATH:$MAVEN_HOME/bin
mvn --version
mvn clean package'''
        echo 'Build Step completed'
      }
    }

  }
}