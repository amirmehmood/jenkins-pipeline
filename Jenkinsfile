pipeline {
  agent any
  stages {
    stage('') {
      steps {
        parallel(
          "stage1": {
            echo 'message 1'
            echo 'message 2'
            
          },
          "stage1a": {
            echo 'message1a'
            
          }
        )
      }
    }
    stage('stage2') {
      steps {
        echo 'message stage 2'
      }
    }
  }
}