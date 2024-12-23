# Get-SSL-at-localhost
In this repo you will come to know how to install SSL certificates in your localhost.

# Create a folder for the certificates
```mkdir -p /etc/certs```

# Get into the folder
```cd /etc/certs```

# OpenSSL Seld-Signed Certificate Command:
```openssl req -new -newkey rsa:4096 -days 3650 -nodes -x509 -subj "/C=NA/ST=NA/L=NA/O=NA/CN=Generic SSL Certificate" -keyout privkey.pem -out fullchain.pem```
