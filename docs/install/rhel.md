# apache install

## References
* https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Managing_Confined_Services/chap-Managing_Confined_Services-The_Apache_HTTP_Server.html

	
##### Install the Apache HTTP server
	yum search httpd
	sudo yum install httpd
	yum list installed | grep httpd

##### See where HTTPD was installed
	whereis httpd

##### Find the httpd.conf file
	sudo find / -name httpd.conf

##### Edit httpd.conf
	sudo vim /etc/httpd/conf/httpd.conf
	/ServerN

##### Add this line to httpd.conf
	ServerName localhost

##### See if a service is listening on port 80
	sudo lsof -ni:80

##### Check the status of the httpd service
	sudo service httpd status

##### Check the run level
	runlevel
	
##### See if httpd is set to start for run levels 0 through 6
	chkconfig --list httpd

##### Set httpd to start in run levels 2, 3, 4, and 5
	sudo chkconfig httpd on

##### See if httpd is set to start for run level 3
	chkconfig --list httpd
	
##### Start the httpd service
	sudo service httpd start

##### See if a service is listening on port 80
	sudo lsof -ni:80
    
##### Install lynx
	sudo yum install lynx

##### Visit the test page for the Apache HTTP server on localhost 
	lynx localhost

##### Install telnet on the EC2 instance
	sudo yum install telnet

##### Telnet to port 80 on localhost
	telnet localhost 80
```c
// Trying 127.0.0.1...
// Connected to localhost.
// Escape character is '^]'.
// ^]
// 
// telnet> q
// Connection closed.
```

