# docker-2048

[![Docker Repository on Quay](https://quay.io/repository/coryallegory/docker-2048/status "Docker Repository on Quay")](https://quay.io/repository/coryallegory/docker-2048)

A fork of [alexwhen's containerized version of 2048](https://github.com/alexwhen/docker-2048), but with multi-platform support (amd64 and arm64).

# run the docker container by pulling the image directly

    docker run -d -p 8080:80 quay.io/coryallegory/docker-2048

# Access the game

    http://127.0.0.1:8080

If you run docker with boot2docker on Mac or Windows, the URL should be:
 
    http://192.168.59.103:8080
