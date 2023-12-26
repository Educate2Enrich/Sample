pipeline {
  agent any
  stages {
    stage('Checkout Stage 1') {
      steps {
        git(url: 'https://github.com/Educate2Enrich/Sample', branch: 'main')
        readFile(file: 'index.html', encoding: 'UTF-8')
      }
    }

  }
}