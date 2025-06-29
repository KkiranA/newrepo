pipeline {

  agent any
  
   environment {
    APP_NAME = 'MyApp'
    DEPLOY_ENV = 'staging'
  


  stages {

    stage('Build') {

      steps {
        sh 'df -PhT'

        echo 'Step 1: Building the application...'

      }

    }

    stage('Test') {

      steps {

        echo 'Step 2: Running tests...'

      }

    }

    stage('Deploy') {

      steps {

        echo 'Step 3: Deploying to staging...'

      }

    }

  }

}
