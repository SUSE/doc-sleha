pipeline {
  agent any
  stages {
    stage('Prepare') {
      steps {
        echo 'Hello User'
        sh '''
echo "Current directory" '''
      }
    }

    stage('Hallo') {
      steps {
        echo 'Hello $JENKINS_USER'
      }
    }

  }
}