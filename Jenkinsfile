pipeline {

 agent any 
 stages{
 stage('build') {
   Steps {
       echo "Running Build Automation"
       sh './gradlew view --no-daemon'
       archieveArtifacts artifacts: 'dis/trainSchedule.zip'
       
     }
   }
 }
}
