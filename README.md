### The following instructions will guide you through the CSR generation process with openssl

### create crs with openssl
```
openssl req -new -newkey rsa:2048 -nodes -keyout abdidarmawan.com.key -out abdidarmawan.com.csr
```
```
Country Name (2 letter code) [AU]:ID
State or Province Name (full name) [Some-State]:DKI Jakarta
Locality Name (eg, city) []:Jakarta      
Organization Name (eg, company) [Internet Widgits Pty Ltd]:PT Abdi Tech
Organizational Unit Name (eg, section) []:IT
Common Name (e.g. server FQDN or YOUR name) []:*.abdidarmawan.com
Email Address []:admin@abdidarmawan.com
```
### check your crs correct
```
https://www.gogetssl.com/online-csr-decoder/
```


### paste or send your csr in your ssl certificate provider
##### Note: 
- save your key and csr files
- You are not required to enter a password or passphrase
- for ssl wildcard *.abdidarmawan.com , for non wildcard www.abdidarmawan.com
- for verification provider will send via email (admin@domain.com,administrator@domain.com) or via CNAME we add record in our dns
