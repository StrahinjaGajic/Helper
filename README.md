# Helper
httpd-vhost
<VirtualHost localhost:8001>
    ServerAdmin postmaster@localhost
    DocumentRoot "C:/xampp/htdocs/wordpress"
    ServerName localhost:8001
</VirtualHost>

<VirtualHost localhost:8002>
    ServerAdmin postmaster@localhost
    DocumentRoot "C:/xampp/htdocs/repulsive-flow-mvc"
    ServerName localhost:8002
 </VirtualHost>

<VirtualHost localhost:8003>
    ServerAdmin postmaster@localhost
    DocumentRoot "C:/xampp/htdocs/test"
    ServerName localhost:8003
</VirtualHost>
httpd.conf
line 58
Listen 8001
Listen 8002
Listen 8003
