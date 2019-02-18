# Nginx mirror setup

Run

```$ docker-compose up```

This will boot 3 nginx-containers, one `proxy`, one `app` and one `mirror` server.

Proxy will proxy requests from localhost:9088 to both `app` and `mirror`.


Run when done, this will cleanup stuff.

```$ docker compose down```