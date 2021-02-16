pipeline {
	agent any   
	stages {
        	stage('test') {
	            steps {
			sh 'pip install pytest'
			sh 'pytest'
	            }
	        }
	}
}
