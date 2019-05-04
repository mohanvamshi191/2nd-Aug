pipeline {
  agent any
  stages {
    stage('master') {
      when {
        branch 'master'
      }
      steps {
        echo 'Print'
      }
    }
    stage('Branch') {
      when {
        branch 'Develop'
      }
      steps {
        echo 'Run tests'
      }
    }
  }
}