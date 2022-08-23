pipeline {
  agent any

  stages {

    stage('TEST1') {
      steps {
        echo 'test1'
      }
    }


     stage('TEST2') {
       steps {
         echo 'test2'
       }
     }
  }

  post {
    fixed {
      echo "Hello"
    }
    failure {
      echo "Failed State"
    }
    cleanup {
      echo "Common steps"
    }
  }

}

