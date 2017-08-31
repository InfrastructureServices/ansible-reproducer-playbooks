# Deploy vsftpd with TLS support and self-signed cert
```
$ vagrant up
$ openssl s_client -connect <ipv4 of the virtual machine>:21 -starttls ftp -tls1_2
```

