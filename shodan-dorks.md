# Shodan Dorks for Security Research

A curated list of Shodan dorks for security research and bug bounty hunting.

### Default Credentials
```
http.title:"Login" "default password"
"default password" port:22,21,23
default credentials
```

### Remote Access and Management
```
remote desktop "port:3389"
vnc port:"5900"
admin port:"8080"
dashboard port:"10000"
```

### IoT and Industrial Systems
```
"SERVER: SQ-WEBCAM" port:80
port:502 Modbus
port:44818 PLC
"Niagara Web Server" port:1911
```

### Exposed Databases
```
port:27017 MongoDB
"redis_version" port:6379
port:9200 elasticsearch
port:5432 PostgreSQL
```

### Cloud Services
```
"Amazon S3" port:443
"kubernetes" port:6443
"docker" port:2375
ssl:"Amazon" port:443
```

### Security Appliances
```
"Firewall" port:443
"VPN" port:1194
"Fortinet" port:443
"Palo Alto Networks" port:443
```

### Misconfigured Servers
```
"authentication disabled" port:445
"XAMPP" port:80
title:"Test Page" port:80
ssl:false port:443
```

### Development and Debugging
```
http.title:"phpMyAdmin"
port:9000 php-fpm
jenkins port:8080
"Git Repository" port:9418
```

### Surveillance Systems
```
product:"Hikvision" port:80
webcam has_screenshot:true
"Server: Camera" port:80
```

### Network Storage
```
"NAS" port:445
"FTP server" port:21
title:"Network Storage" port:80
```

### HTTP Redirections
```
http.location:"https://*"
http.location:*
http.redirect:1
```