pipeline {
	agent any {
		states {
			stage('Build') {
				steps {
					sh 'echo Stage1 : this is the build stage'
				}
			}
			stage('Test') {
				sh 'echo Stage2: this is the test stage'
			}
			stage('Deploy') {
				sh 'echo Stage3 : this is deploy stage'
			}
		}
	}
}