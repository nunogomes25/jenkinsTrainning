pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('01 - Jenkinsfile - First Pipeline') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}