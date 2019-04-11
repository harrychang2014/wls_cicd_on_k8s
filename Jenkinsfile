pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      environment {
        IMAGE_NAME = 'harrychang2014/wls_cicd_on_k8s'
      }
      steps {
        echo 'Hello pipeline!'
      }
    }
  }
}