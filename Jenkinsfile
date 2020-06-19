pipeline {
  agent any
  stages {
    stage('stage 1 ') {
      steps {
        echo 'This is stage 1 '
        sh 'echo "Build Number: $BUILD_NUMBER and DEMO: $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}