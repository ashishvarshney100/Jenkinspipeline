pipeline {
	agent any 
	stages {
		stage("Print string by code pulling from git") {
			steps {
				echo "Hello world!!!!!!!!!!"
			}
		}
	}
}