pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''export MAVEN_HOME=/usr/local/Cellar/maven/3.6.3_1
export PATH=$PATH:$MAVEN_HOME/bin
mvn clean package'''
      }
    }

    stage('Test') {
      steps {
        sh 'echo "Testing processing"'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "Deploy processing"'
      }
    }

  }
}