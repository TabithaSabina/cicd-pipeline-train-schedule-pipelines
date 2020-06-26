Pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automatically'
        sh './gradlewbuild--no-daemon'
        archiveArtifacts artifacts:'dist/trainSchedule.zip'
     }
    }
   }
  }
  
