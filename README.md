# Template for deploy [metabase](https://metabase.com) with docker and nginx

## Steps to deploy

1. Clone this repository
2. Copy .env.example to .env
3. Set up your credentials at .env
4. Run `docker-compose up` or ```docker-compose up -d``` for daemon

## Some considerations
By default, this template will use PostgresSQL with the default database for Metabase settings. For you to work with your data, after installation you need to connect your source data, like MySQL, Postgres, redshift, wherever.