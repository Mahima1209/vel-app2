//this is my 1st Jenkinsfile
pipeline {
	agent {
		label "built-in"
	}
	stages {
		stage ('deploy-index') {
			steps {
				sh "rm -rf *"
				sh "cp -r index.html /var/www/html/"
				sh "chmod -R 777 /var/www/html/index.html"
			}
		}
	}
}
