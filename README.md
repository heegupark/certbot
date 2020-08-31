# certbot

# https setting using certbot
```
sudo apt install software-properties-common
sudo add-apt-repository universe
sudo add-apt-repository ppa:certbot/certbot
sudo apt update
sudo apt install certbot python3-certbot-nginx
```

# certbot refresh
```
sudo certbot -—nginx
```

# certbot renew
```
sudo certbot renew
```

# certbot renew test
```
sudo certbot renew --dry-run

```

# certbot expiration date check
```
sudo certbot certificates
```
