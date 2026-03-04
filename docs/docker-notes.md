# Docker Workflow Validation Notes

## Hello World Test
Ran `docker run hello-world`
Output included:
Hello from Docker!
This message shows that your installation appears to be working correctly.

## Postgres Container
Command used:
docker run -d --name pg-prework -e POSTGRES_PASSWORD=prework -p 5433:5432 postgres:15-alpine

## Postgres Startup Logs
Ran `docker logs pg-prework`
LOG: database system is ready to accept connections

## Stop and Restart
Ran:
docker stop pg-prework
docker restart pg-prework