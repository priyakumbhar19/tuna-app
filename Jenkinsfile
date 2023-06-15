pipeline {
 agent {
    label {
	 label "slavessh"
	 customWorkspace "/mnt/jenkinsfile"
	}
 }
 stages {
      stage ("stage1") {
	  steps {
	         sh "sudo service httpd start"
			 sh "sudo cp -r index.html >> /var/lib/html"
			 sh "chmod -R 777 /var/lib/html/index.html
	  }
	  }
 }
