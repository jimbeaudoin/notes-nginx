# notes-nginx

### Diffie-Hellman (DH) key exchange parameters
```sh
cd /etc/nginx
# Generate a new key
openssl dhparam -out dhparam.pem 4096

# Setup ssl.conf
ssl_dhparam /etc/nginx/dhparam.pem;
```
