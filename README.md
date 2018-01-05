# Leave me alone sweater
static page

to renew cert

```
sudo certbot renew
```

to make new cert

```
certbot certonly --force-renewal -a webroot -w /var/www/leavemealonesweater -d www.leavemealonesweater.com -w /var/www/leavemealonesweater -d leavemealonesweater.com
```

to make sure nginx is reloaded after certs are renewed: https://www.guyrutenberg.com/2017/01/01/lets-encrypt-reload-nginx-after-renewing-certificates/

Template from [Start Bootstrap - Creative](https://startbootstrap.com/template-overviews/creative/)
