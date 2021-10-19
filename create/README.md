## Create database ##
# Run docker container with PostgreSQL database #
`docker run --name sql-workshop -p 5432:5432 -e POSTGRES_PASSWORD=pass -d postgres`
