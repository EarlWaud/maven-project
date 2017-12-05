pipeline {
	agent any
	stages {
		stage ('Initialize') {
			steps {
				sh '''
					echo "PATH = ${PATH}"
					echo "M2_HOME = ${M2_HOME}"
					'''
			}
		}
		stage ('Pull') {
			steps {
				echo 'Pulling container images....!'
			}
		}
		stage ('Build') {
			steps {
				echo 'Building new image....!'
			}
		}
		stage ('Push') {
			steps {
				echo 'Pushing new image ....!'
			}
		}
	}
}
