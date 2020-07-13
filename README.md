### The following instructions will guide you through the CSR generation process with openssl

### create crs with openssl
```
openssl req -new -newkey rsa:2048 -nodes -keyout abdidarmawan.com.key -out abdidarmawan.com.csr
```
```
Country Name (2 letter code) [AU]:ID
State or Province Name (full name) [Some-State]:Jakarta
Locality Name (eg, city) []:Keboon Jeruk
Organization Name (eg, company) [Internet Widgits Pty Ltd]:Abdi Tech
Organizational Unit Name (eg, section) []:
Common Name (e.g. server FQDN or YOUR name) []:abdidarmawan.com
Email Address []:abdid-cool@gmail.com
```
#### Note: You are not required to enter a password or passphrase
