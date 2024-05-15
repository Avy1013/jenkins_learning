pipeline {
  agent any
  stages {
    stage('code checkout') {
      steps {
        git(url: 'https://github.com/Avy1013/jenkins_learning/tree/main', branch: 'main')
      }
    }

    stage('sh') {
      steps {
        sh 'ls -la'
      }
    }

  }
}