pipeline {
	agent {
		docker {
			image 'maven:3-alpine' 
			args '-v /root/.m2:/root/.m2' 
		}
	}

	stages {
		stage('Build Stage') {
			steps {
				echo "Building Maven Project"
				sh 'mvn clean install'
			}
		}
	}
}
