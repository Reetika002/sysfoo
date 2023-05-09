pipeline {
  agent {
    docker {
      image 'maven:3.6.3-jdk-11-slim'
    }

  }
  stages {
    stage('build') {
      agent any
      steps {
        sleep 2
      }
    }

    stage('package') {
      steps {
        sleep 2
      }
    }

    stage('test') {
      steps {
        sleep 2
      }
    }

  }
}