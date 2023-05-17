pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
        
        echo 'App'
        sh 'python app.py'
      }
    }
    stage('Test') {
      steps {
        echo 'Test'
        
      }
     
    }
  }
}
