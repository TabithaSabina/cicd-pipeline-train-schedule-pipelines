pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automatically'
        sh './gradlew build--no-daemon'
        archiveArtifacts artifacts:'dist/trainSchedule.zip'
     }
    }
   }
  }
  
