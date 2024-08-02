## steps
1. docker-compose up

2. npx hasura-cli console

3. psql -h localhost -p 4446  -U user -d reef_dev

### we wil notice there is a race between pg and hasura and eventually hasura will restart after failing.