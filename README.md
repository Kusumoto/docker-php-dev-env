# Docker developing environment for PHP Developer
### Images Contain
- Apache Web Server 2.4.10
- PHP 7.0
- MySQLi Extension
- PDO Extension
- MongoClient Extension
- xdebug Extension

### How to use
1. Clone this repository
2. Use Command
```bash
docker build -t php-dev [Dockerfile location]
docker run --name php-dev -d -p 80:80 -v [develop file location]:/var/www/html/ php-dev:latest
```
