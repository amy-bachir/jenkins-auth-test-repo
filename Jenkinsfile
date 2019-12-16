pipeline {
  stages {
    stage('CICD Initialize') {
      steps {
        script{
          echo "hello world"
        }
      }
    }
  }
  post {
      always {
        dir (WORKSPACE){
          echo "POST ALWAYS STAGE"
        }
      }
    }
  }
