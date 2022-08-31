pipeline {
	agent any
	stages {
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
	post {
		always {
			echo 'Im awasome. I always run'
		}
		success {
			echo 'I run when you are successful'
		}
		always {
			echo 'I run when you fail'
		}
	}
}
