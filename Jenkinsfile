pipeline {
agent any
stages {
 stage ( 'Build' ) {
 steps {
 echo "build automation"
 sh './gradlew build --no-daemon'
 archiveArtifacts Artifacts: 'dist/trainSchedule.zip'
 }
}
}

}
