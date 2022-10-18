# Keycloak SPI

Example of Keycloak SPI implementation. Check the password over dictionary

## build

docker build --rm -t <CONTAINER_NAME>:<TAG> .

## run

docker run -it --rm -p 8080:8080 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=test1 -e DB_VENDOR=h2 <CONTAINER_NAME>:<TAG>

### Project by

[![Rossonet s.c.a r.l.](https://raw.githubusercontent.com/rossonet/images/main/artwork/rossonet-logo/png/rossonet-logo_280_115.png)](https://www.rossonet.net)


