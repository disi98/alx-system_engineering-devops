# Web Infrastructure Design

| 0. Simple web stack | 1. Distributed web infrastructure | 2. Secured and monitored web infrastructure |
| ------------------- | --------------------------------- | ------------------------------------------- |
| **Contain**:
	1 server
	1 web server (Nginx)
	1 application server
	1 application files (your code base)
	1 database (MySQL) | 	**Contains**:
					2 servers
					1 web server (Nginx)
					1 application server
					1 load-balancer (HAproxy)
					1 set of application files (your code base)
					1 database (MySQL)| **Contaions:
									3 firewalls
									1 SSL certificate to serve www.foobar.com over HTTPS
									3 monitoring clients (data collector for Sumologic or other monitoring services) |
