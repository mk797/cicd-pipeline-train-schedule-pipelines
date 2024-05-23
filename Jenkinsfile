pipeline{
agent any
stages{
  stage('Build'){
steps{
echo 'Building started'
sh './gradlew build --no-daemon'
archiveArtifacts artifacts: 'dist/trainSchedule.zip'
}
}

}

}
