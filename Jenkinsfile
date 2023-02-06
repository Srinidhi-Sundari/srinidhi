pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git(url: 'https://github.com/Srinidhi-Sundari/srinidhi', branch: 'main')
      }
    }

    stage('list files') {
      steps {
        sh '''ls -ls

echo "what\'s up"'''
      }
    }

  }
}