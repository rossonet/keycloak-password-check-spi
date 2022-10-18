# Keycloak SPI implementation. Check the new password in a remote dictionary

Example of Keycloak SPI implementation. Check the password over dictionary

## build

```
docker build --rm -t <CONTAINER_NAME>:<TAG> .
```

## build from repository

```
docker build --rm -t <CONTAINER_NAME>:<TAG> https://github.com/rossonet/keycloak-password-check-spi.git#main
```

## run

```
docker run -it --rm -p 8080:8080 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=test1 -e DB_VENDOR=h2 <CONTAINER_NAME>:<TAG>
```

### Project by

[![Rossonet s.c.a r.l.](https://raw.githubusercontent.com/rossonet/images/main/artwork/rossonet-logo/png/rossonet-logo_280_115.png)](https://www.rossonet.net)


