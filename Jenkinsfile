pipeline {
	agent any

	// agent {
	// 	docker  {
    //         image 'maven:3.6.3'
    //     }
    // }
	
	stages{
		stage('Build') {
			steps {
				// sh 'mvn --version'
				// sh 'docker version'
				echo "Build"
				echo "$PATH"
				echo "Build Number - $env.BUILD_NUMBER"
				echo "$env.BUILD_ID"
				echo "$env.JOB_NAME"
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
