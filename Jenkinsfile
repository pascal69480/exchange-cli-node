pipeline {
    agent any
    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm ci'
              } 
       }
        stage('Unit Test') {
            steps {
                sh 'npm test'
            }
      } 
    } // stages
} // pipeline
