pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M398"
    }

    stages {
        stage('Echo version'){
            steps {
                sh 'echo print maven version'
                sh 'mvn -version'
            }
        }
    }
}
