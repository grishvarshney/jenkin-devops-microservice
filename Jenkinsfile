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
