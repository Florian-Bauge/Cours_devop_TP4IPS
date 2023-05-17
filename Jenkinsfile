pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
        sh 'pip install -r requirements.txt'
      }
      steps {
        echo 'App'
        sh 'python app.py'
      }
    }
    stage('Test') {
      steps {
        echo 'Test'
        sh 'python test.py'
      }
      post {
        always {
          junit 'test-reports/*.xml'
        }
      }
    }
  }
}
