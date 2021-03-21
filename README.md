# liRedditClone

# How to start and stop postgres sever
pg_ctl -D /usr/local/var/postgres start
pg_ctl -D /usr/local/var/postgres stop

# Then run yarn watch - Monitors changes inside src/ folder and converts .ts files to .js

# Finally run yarn dev - Monitors for changes inside the dist/index.js file  

https://www.robinwieruch.de/postgres-sql-macos-setup

# To run postgres commands type psql <DBName> e.g. psql lireddit