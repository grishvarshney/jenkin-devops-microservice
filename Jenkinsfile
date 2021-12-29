pipeline {
	agent any
	stages{
		stage('Build') {
			steps {
				echo "Build"
			}
			
		}
		stage('Test') {
			steps {
				echo "Test"
			}
				
			}
		stage('Integration Test') {
			steps {
				echo "Integration Test"
			}
				
			}
			
	}

	post{
		success{
				echo "success"
				}
		always{
				echo "always"
			}
		failure{
				echo "failure"
			}
			
	}
	
}
