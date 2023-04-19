# yourls

Deploy Yourls using docker-compose

## Requirements

1. Need to modify docker-compose.yml

```
MYSQL_ROOT_PASSWORD: ROOT_PASSWORD
MYSQL_DATABASE: DATABASE
MYSQL_USER: USER
MYSQL_PASSWORD: PASSWORD
```

2. Need to update certs/fullchain.pem and certs/privkey.pem

3. Need to modify web/html/user/config.php
