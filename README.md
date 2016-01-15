# Installation 

`sudo -i`

`git pull https://github.com/Farioko/multhost.git`

`chmod 700 multhost/radera_elev multhost/skapa_elev`

`ln -s /root/multhost/skapa_elev /sbin/skapa_elev`

`ln -s /root/multhost/radera_elev /sbin/radera_elev`

# Configuration

`vi multhost/multhost.conf`

```bash
mysqlpassword="password"
basedir="/var/www/html/elever"
domain="example.org"
serveradmin="user@example.org"
```

`chmod 600 multhost/multhost.conf`
