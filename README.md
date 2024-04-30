# Generic Docker Boilerplate

### Instructions
```
git clone https://github.com/zangarmarsh/generic-docker-boilerplate && \
cd generic-docker-boilerplate && \
# <optional> vi .env && \
# <optional> echo "127.0.0.1 d.test # Docker Generic Boilerplate" | sudo tee -a /etc/hosts && \
docker compose up --build
```

### Comes out of the box with:
- PHP 8.3 FPM
- nginx@latest
- clickhouse@latest
- mariadb@latest
- tidb@latest
- phpmyadmin@latest
- mongo@latest
- mongo-express@latest
- redis@latest
- redis-stat@latest
- gearmand@latest
- mailhog@latest
