# PostgreSQL

DB copied from here: https://github.com/SeaQL/seaography/edit/main/examples/postgres/README.md

## Getting started

To create a new sakila database:

1. Create the database: `psql -q postgres://username:password@localhost/postgres -c 'CREATE DATABASE "sakila"'`
2. Create schema: `psql -q postgres://username:password@localhost/sakila < sakila-schema.sql`
3. Add data: `psql -q postgres://username:password@localhost/sakila < sakila-data.sql`
