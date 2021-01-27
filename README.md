# Postgress Cheatsheet

- sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list'
- wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -
- sudo apt-get update
- sudo apt-get install postgresql
- sudo -i -u postgres
- psql
- sudo -u postgres createuser --interactive
- sudo -u postgres createdb blog
- sudo apt-get install pgadmin4


## Django issues
- sudo apt install libpq-dev python3-dev
- pip install psycopg2
