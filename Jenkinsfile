pipeline {
  agent any
  stages {
   stage {'BUILDING THE PROCES'} {
    steps {
     echo 'Running the process with automation tool'
     sh './gradlew build --no-daemon'
     archiveArtifacts artifacts: 'dist/trainSchedule.zip'
   }
  }
  }
  }
