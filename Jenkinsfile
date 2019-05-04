pipeline {
  agent any
  stages {
    stage('Master') {
      when {
        branch 'master'
      }
      steps {
        echo 'Print'
      }
    }
    stage('Branch') {
      when{
        branch 'Develop'
      }
      steps {
        echo 'Run tests'
      }
    }
  }
}
