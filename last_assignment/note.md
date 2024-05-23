# PostgreSQL

```
username: bishaltwr
password: MjMzNjMtYmlzaGFs
```

- Downloading setup file and running:
```bash
wget https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DB0231EN-SkillsNetwork/labs/Final%20Assignment/postgres-setup.sh

chmod +x  ./postgres-setup.sh

./postgres-setup.sh
```

## Task 1.1: Find the settings in PostgreSQL

- What is the maximum number of connections allowed for the postgresSQL for this server?
    - Answer: 100
- postgresql.conf file

> Location: /home/project/postgres/data/pgdata/postgresql.conf

![max-connections](max-connections.png)

# Exercise 1.2 User management
- Perform using CLI not GUI

## Task 1.2: Create a User

```bash
psql --username=postgres --host=localh 
```
![create_user](create-user.png)

## Task 1.3 - Create a Role
![create_role](create-role.png)

## Task 1.4 - Grant privileges to role
![grant](grant-privs-to-role.png)

## Task 1.5 - Grant role to an user
![grant_role_to_user](image.png)

# Exercise 1.3 - Backup

## Task 1.6 - Backup a database on PostgreSQL server

- Backup tolldata using PGADMIN GUI
![alt text](<pgadmin_gui.png>)

![backup](backup-database.png)

# MySQL

# Exercise 2.1 - Setup the lab environment

```
username: bishaltwr
password: MTA2OTItYmlzaGFs
```

## Task 2.1 - Restore MySQL server using a previous backup

![restore](database-restore.png)

## Task 2.2 - Find the table data size

![table_size](table-data-size.png)

# Exercise 2.3 - Indexing

## Task 2.3 - Baseline query performance

![baseline](query-base-line.png)

## Task 2.4 - Create an index

![index-creation](index-creation.png)

## Task 2.5 - Document the improvement in query performance

![query-indexed](query-indexed.png)

# Exercise 2.4 - Storage Engines

## Task 2.6 - Find supported storage engines

![engines](storage-engines.png)

## Task 2.7 - Find the storage engine of a table 

![innodb](storage-engine-type.png)

# Exercise 3.1 - Prepare the lab environment

- Download the file billing.csv

## Task 3.1 - Restoree the table billing
![data restored](restore-table.png)

# Exercise 3.3 - Create a view

## Task 3.2 - Create a view named basicbilldetails with columns customerid, month, billedamount

![create view](create-view.png)

# Exercise 3.4 - Indexing

## Task 3.3 - Baseline query performance

![baseline](query-base-line-db2.png)

## Task 3.4 - Create an index

![create index](index-creation-db2.png)


## Task 3.5 - Document the improvement in query performance

![improvement](query-after-index.png)