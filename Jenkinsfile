pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
        sh 'pip install -r requirements.txt'
        echo 'App'
        sh 'app.py'
      }
    }
    stage('Test') {
      steps {
        echo 'Test'
        
      }
     
    }
  }
}
