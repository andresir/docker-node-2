pipeline {
	agent any

	stages {
		stage('Del') {
			steps{
				sh "docker image ls"
				sh "docker rmi dev-rtsm.ottopay.id/hellonode:latest"
			}
		}
	}
}
