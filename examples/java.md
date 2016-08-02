# Java
## SSL
Unsigned Certificate
```bash
java \
  ... \
  -Djavax.net.ssl.trustStore=PATH_TO_TRUSTSTORE.jks \
  -Djavax.net.ssl.trustStorePassword=TRUSTSTORE_PASSWORD \
  ... \
  MainClass \
  Args...
```

## Kerberos
```bash
java \
  ... \
  -Djava.security.auth.login.config=PATH_TO_JAAS.conf  \
  ... \
  MainClass \
  Args...
```
