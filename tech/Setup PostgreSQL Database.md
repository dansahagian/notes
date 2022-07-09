# Setup PostgreSQL Database
```shell
psql -U user -d postgres
sudo -u postgres psql
CREATE DATABASE $DB;
CREATE ROLE $ROLE WITH PASSWORD $PW;
ALTER ROLE $ROLE WITH CREATEDB LOGIN;
GRANT ALL ON DATABASE $DB TO $ROLE;
```

#postgres