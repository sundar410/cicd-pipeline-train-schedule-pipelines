pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                echo 'Build Automation Scipt'
                sh './gradlew build --no-daemon' 
                archiveArtifacts 'dist/trainSchedule.zip'
            }
        }
    }
}
