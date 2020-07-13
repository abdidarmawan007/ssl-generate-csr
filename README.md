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
Common Name (e.g. server FQDN or YOUR name) []:*.abdidarmawan.com
Email Address []:abdi-cool@gmail.com
```

### paste your csr in your ssl certificate provider
##### Note: 
- save your key and csr files
- You are not required to enter a password or passphrase
- for ssl wildcard *.abdidarmawan.com , for non wildcard www.abdidarmawan.com
- for verification provider will send via email (admin@domain.com,administrator@domain.com) or via CNAME we add record in our dns
