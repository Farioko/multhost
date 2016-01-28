# Installation 

`cd /opt`

`sudo git clone https://github.com/Farioko/multhost.git`

`sudo chmod 700 multhost/radera_elev multhost/skapa_elev`

`sudo visudo`

Konkatenera *:/opt/multhost* med strängen *secure_path*

# Konfiguration

`sudo vi multhost/multhost.conf`

```bash
mysqlpassword="password"
basedir="/var/www/html/elever"
domain="example.org"
serveradmin="user@example.org"
```

`sudo chmod 600 multhost/multhost.conf`
