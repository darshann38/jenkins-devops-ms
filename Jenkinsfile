//SCRIPTED

//DECLATATIVE

pipeline {
	agent any
	stages{

		stage('build'){
			steps{
				echo "Build"
			}	
		}
		
		stage('test'){
			steps {
				echo "Test"
			}
		}
		
		stage('integration test'){
			steps{
				echo "Integration Test"
			}
			
		}
	} 
	
	post {
		always{
			echo "i run always"
		}
		success{
			echo "i run only when it is success"
		}
		failure {
			echo "i run when you fail"
		}
	}
}

