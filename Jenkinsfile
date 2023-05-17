pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
        
        echo 'App'
        
      }
    }
    stage('Test') {
      steps {
        echo 'Test'
        
      }
      post {
        always {
          junit 'test-reports/*.xml'
        }
      }
    }
  }
}
