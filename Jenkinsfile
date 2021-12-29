pipeline {
	agent any
	stages{
		stage('Build') {
				echo "Build"
				}
		stage('Test') {
				echo "Test"
			}
		stage('Integration Test') {
				echo "Integration Test"
			}
			
	}

	post{
		success{
				echo "Build"
				}
		always{
				echo "Test"
			}
		failure{
				echo "Integration Test"
			}
			
	}
	
}
