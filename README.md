Example app of `docker-compose` started with bash script that causes issue with env variables.

Run `bash up.sh` command

## The problem is that you cannot use `DOCKER_DB_PORT=${DB_PORT}` syntax in .env file. Hardcoded variable `DOCKER_DB_PORT=3307` works.