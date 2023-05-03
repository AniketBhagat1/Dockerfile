pipeline {
  agent any
  stages {
    stage('Git checkout') {
      steps {
        sh 'git clone "https://github.com/AniketBhagat1/Dockerfile.git"'
      }
    }

    stage('build') {
      steps {
        sh 'echo "hi"'
      }
    }

  }
}