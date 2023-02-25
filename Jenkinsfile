/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'php:8.1.11-alpine' } }
    stages {
	stage('PHP version') {
        	steps {
			sh 'php --version'
		}
	}
	stage('Env') {
		steps {
			env
		}
       	}
    }
}



