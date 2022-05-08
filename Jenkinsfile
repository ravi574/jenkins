pipeline {
	agent any 
	stages {
		stage('Build') {
			steps {
				sh '''
					echo Stage1 : this is the build stage
					sleep 5
				   '''
			}
		}
		stage('Test') {
			steps {
				sh '''
					echo Stage2: this is the test stage
					sleep 5
					'''
			}
		}
		stage('Deploy') {
			steps {
				sh '''
					echo Stage3 : this is deploy stage
					sleep 5
					'''
			}
		}
	}	
}