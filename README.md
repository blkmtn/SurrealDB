# Start Here

1. Run `docker compose up -d`

2. To get into the CLI use `docker exec -it surrealdb /surreal sql -c http://localhost:8000 -u root -p root --ns test --db test --pretty`

3. Get some data into the db by following this tutorial:
https://medium.com/featurepreneur/surreal-db-the-ultimate-cloud-database-78f0c2dfde1d

5. Use cntrl + c to exit the CLI tool

4. Spin down your instance using `docker compose down`

More docs at https://surrealdb.com/