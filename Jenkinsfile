pipeline {

  agent any
  
   environment {
    APP_NAME = 'MyApp'
    DEPLOY_ENV = 'staging'
   }
  


  stages {

    stage('Build') {

      steps {
        sh 'df -PhT'

        echo "Step 1: Building the application: ${APP_NAME}"

      }

    }

    stage('Test') {

      steps {

       echo "Step 2: Running tests for ${APP_NAME}..."

      }

    }

    stage('Deploy') {

      steps {

        echo "Step 3: Deploying ${APP_NAME} to ${DEPLOY_ENV}..."

      }

    }

  }

}
