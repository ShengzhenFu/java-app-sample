```bash
mvn package
```

```bash
mvn test
```

requires a mysql db
```bash
default appName = 'fruit-api'
default dbName = 'fruits'
default username = 'fruitapi'
default password = '${appName}-DB'
SPRING_DATASOURCE_URL: `jdbc:mysql://${db.clusterEndpoint.hostname}:${db.port}/${dbName}`
```