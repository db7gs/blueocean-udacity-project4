pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'test1'
      }
    }

    stage('deploy to S3') {
      steps {
        s3Upload 'static-jenkins'
      }
    }

  }
}