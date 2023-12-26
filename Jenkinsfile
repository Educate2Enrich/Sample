pipeline {
  agent any
  stages {
    stage('Checkout') {
      agent any
      steps {
        git(url: 'https://github.com/Educate2Enrich/Sample', branch: 'main')
      }
    }

  }
}