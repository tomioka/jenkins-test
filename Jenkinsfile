pipeline {
  agent any
  stages {
    stage('build') {
      steps {
 	sh "echo 'hi from b1!'"
        }
      }
    }
    post {
      always {
        deleteDir()

      }
    }
}

