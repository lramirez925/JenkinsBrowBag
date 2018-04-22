pipeline {
  agent {
    docker {
      image 'ortussolutions/commandbox'
      args '-u root'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo \'In Build Step\''
        sh 'ls'
        sh 'cd code'
        sh 'ls'
        sh 'pwd'
        sh 'box version'
      }
    }
  }
}