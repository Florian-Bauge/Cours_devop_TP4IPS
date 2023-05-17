pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
        bat 'pip install -r requirements.txt'
        echo 'App'
        bat 'python app.py'
      }
    }
    stage('Test') {
      steps {
        echo 'Test'
        
      }
     
    }
  }
}
