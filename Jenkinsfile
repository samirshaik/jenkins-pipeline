pipeline {
	agent any

	stages {
		stage('Build Stage') {
			steps {
				echo "Building Maven Project"
				sh 'mvn clean install'
			}
		}
	}
}
