# Web Infrastructure Design

| 0. Simple web stack | 1. Distributed web infrastructure | 2. Secured and monitored web infrastructure |
| ------------------- | --------------------------------- | ------------------------------------------- |
| **Contain**: <br/>1 server<br/>1 web server (Nginx)<br/>1 application server<br/>1 application files (your code base)<br/>1 database (MySQL) | **Contains**:<br/>2 servers<br/>1 web server (Nginx)<br/>1 application server<br/>1 load-balancer (HAproxy)<br/>1 set of application files (your code base)<br/>1 database (MySQL) | **Contaions:**<br/>3 firewalls<br/>1 SSL certificate to serve www.foobar.com over HTTPS <br/>3 monitoring clients (data collector for Sumologic or other monitoring services) |
