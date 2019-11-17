## Usage
### start server
```bash
$ docker-compose up -d
```

### connect client
```bash
$ docker-compose exec db mysql -u root
```

### connect console
```bash
$ docker-compose exec db bash
```

### sync SQL file
```bash
$ touch sql/sample.sql
$ docker-compose exec db bash
$ mysql -u root < /sql/sample.sql
```
