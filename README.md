#

Steps to setup

1.	Run docker-compose up
2.  Login to http://localhost:9000
3.  Login with default credentials - admin/admin
4.	Generate a user token
5.	Paste the below attributes in your gradle.properties
	sonar.host.url=http://localhost:9000
	sonar.login=<your generated token>
6.  Run the sonar task using your gradle