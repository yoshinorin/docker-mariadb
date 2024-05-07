# MariaDB docker image

Docker image for MariaDB.

# Supported version

|version|OS|
|---|---|
|10.3.5|Debian|
|10.3.7|Debian|
|10.4.2|Debian|
|10.4.7|Debian|
|10.5.4|Ubuntu|
|10.6.3|Ubuntu|
|10.6.8|Ubuntu(focal)|
|10.6.10|Ubuntu(focal)|
|10.11.2|Ubuntu(jammy)|
|10.11.3|Ubuntu(jammy)|
|10.11.4|Ubuntu(jammy)|
|10.11.5|Ubuntu(jammy)|
|10.11.6|Ubuntu(jammy)|
|10.11.7|Ubuntu(jammy)|

# Usaga

```sh
// 10.6.8+
docker run -it ghcr.io/yoshinorin/docker-mariadb:<version>

// 10.6.3
docker run -it yoshinorin/docker-mariadb:<version>
```