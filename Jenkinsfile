pipeline {
  agent any
  stages {
    stage('Chekout Code') {
      steps {
        git(url: 'https://github.com/RecepKarayigit/JenkinsTraining', branch: 'main')
      }
    }

    stage('Show the directory list') {
      steps {
        sh 'ls -la'
      }
    }

  }
}