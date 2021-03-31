pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''export MAVEN_HOME=/usr/local/Cellar/maven/3.6.3_1/
export PATH=$PATH:$MAVEN_HOME/bin
mvn --version
mvn clean package'''
      }
    }

  }
}