pipeline {
  agent any
  stages {
    stage('build') {
      steps {
       echo 'build'
      }
      steps{
       sh 'pip install -r requirements.txt'
      }
    }
    stage('test') {
      steps {
        echo 'test'
      }
           steps {
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
