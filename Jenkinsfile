pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M98"
    }

    stages {
        stage('maven print'){
            steps{
                sh 'echo maven version print'
                sh 'mvn -version'
            }
       
        }
    }
}
