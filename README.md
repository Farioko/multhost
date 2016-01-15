# Installation 

`sudo -i`

`git pull https://github.com/Farioko/multhost.git`

`chmod 700 multhost/radera_elev multhost/skapa_elev`

`vi .bashrc`

Lägg till följande rad längst ner i filen.

`export PATH="$PATH:/root/multhost"`

# Configuration

`vi multhost/multhost.conf`

```bash
mysqlpassword="password"
basedir="/var/www/html/elever"
domain="example.org"
serveradmin="user@example.org"
```

`chmod 600 multhost/multhost.conf`
