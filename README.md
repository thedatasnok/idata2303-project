# IDATA2303 Project

Mandatory project for the course Data modeling and database applications (IDATA2303) at NTNU.

Some of the requested features regarding security is not supported in SQLite, therefore a docker compose file for running Postgres is present. 

## Setting up

1. Install Docker Desktop

2. Install Anaconda
  - Open the Anaconda prompt as an administrator and run: `conda install ipython-sql conda-forge psycopg2 sqlalchemy`

3. Start the postgres database service using `docker compose up -d`

4. Run cells in the notebook
