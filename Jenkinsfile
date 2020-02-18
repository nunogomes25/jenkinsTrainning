pipeline {
    agent { 
		docker { 
			image 'alpine:latests' 
		} 
	}
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}