pipeline {

agent any

stages {
	stage('SCM') {
		steps  {
			echo "git pull my code step1"
			echo "git pull my code step2"
		}
	}

	stage('Deploy') {
		steps { 
			echo "deploying my code"
		}
	}	

	stage('Test') {
		steps {
			echo "test my final webapp"
		}
	}

	stage('Deploy to Prod') {
		steps {
			echo "my final webapp to prod"
		}
	}

}

}