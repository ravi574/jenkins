pipeline {
	agent any 
	stages {
		stage('Build') {
			steps {
				sh 'echo Stage1 : this is the build stage'
			}
		}
		stage('Test') {
			steps {
				sh 'echo Stage2: this is the test stage'
			}
		}
		stage('Deploy') {
			steps {
				sh 'echo Stage3 : this is deploy stage'
			}
		}
	}	
}