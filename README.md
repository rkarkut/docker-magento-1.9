# Docker for Magento 1.9

## Configuration

host: http://localhost:8000  
PhpMyAdmin host: http://localhost:8080

## Database

Database access:  
host: magento_19_mysql  
user: dev  
password: dev  
port: 3306

## Admin panel

url: http://localhost:8000/admin/  
login: admin  
password: TestApp776


## Installation:

1. Run docker container:

```docker-compose up```

2. Install modman

```bash < <(wget -q --no-check-certificate -O - https://raw.github.com/colinmollenhour/modman/master/modman-installer)```

3. Enable modman

```modman init```

4. Install GetResponse plugin:

```modman clone https://github.com/GetResponse/magento -b 1.9```
