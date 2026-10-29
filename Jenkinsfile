pipeline {
    agent any
 
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Jenkins" > output.txt'
                archiveArtifacts artifacts: 'output.txt'
            }
        }
    }
}
