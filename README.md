# traefik setup

A basic traefik setup

## installation

1. clone repo
2. create directory `./etc/` and `./etc/certs` if you plan to use https
3. copy `traefik.example.yml` to `./etc/traefik.yml` and adjust configuration
4. copy `dynamic.example.yml` to `./etc/dynamic.yml` and adjust configuration
5. start traefik with `docker-compose up -d`
