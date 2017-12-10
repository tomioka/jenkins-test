pipeline {
  agent any
  stages {
    stage('build') {
      steps {
 	sh "echo 'hi!'"
        }
      }
    }
    post {
      always {
        deleteDir()

      }
    }
}

