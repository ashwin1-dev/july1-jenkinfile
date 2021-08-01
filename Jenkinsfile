pipeline {
	agent any
		stages {
			stage('Build') {
			steps {
				sh 'sudo rm -rf /var/www/html'
				sh 'sudo yum install httpd'
				sh ' sudo systemctl start httpd'
				sh ' sudo git clone https://github.com/ashwin1-dev/1-july.git  /var/www/html'

				}
				}
			}
	}
