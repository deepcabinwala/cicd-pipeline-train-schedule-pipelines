

pipeline {
    agent any
    stages {
        stage('Buid') {
          steps {
            script {
              sh "./gradlew build"
            }
          }
        }
        stage('Archive') {
          steps {
            script {
              sh "cp dist/trainSchedule.zip /tmp"
            }
          }
        }
    }
}
