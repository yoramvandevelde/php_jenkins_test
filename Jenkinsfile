/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'php:8.1.11-alpine' } }
    stages {
        stage('build') {
            steps {
                stage('PHP version') {
			sh 'php --version'
		}
		stage('Env') {
			env
		}
            }
        }
    }
}


