# Docker Compose Configs

## Set Environment
1. Create a file `.env`
2. Add necessary environment variables in .env

ex:
```
STACK_VERSION=7.8.0
ELK_PASS=<desierd_passwd>
```

## Build and run apps with Compose

1. Run app in background
    * `docker-compose up -d`
2. View the status
    * `docker-compose ps`
3. Down all the services (optional)
    * `docker-compose down`
    * `docker-compose down --volumes` to remove the data volume used



## Referance
1. https://docs.docker.com/compose/gettingstarted/
2. https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html