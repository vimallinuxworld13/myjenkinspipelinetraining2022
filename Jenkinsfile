pipeline {

agent any

stages {
	stage('SCM') {
		steps  {
			echo "git pull my code for java app"
			git 'https://github.com/vimallinuxworld13/simple-java-maven-app.git'
		}
	}

	stage('Build') {
		steps { 
			sh 'mvn clean package'
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