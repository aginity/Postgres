# Postgres Package Summary

|Package Name| Package Description| Number of Queries in Package|
|------------|--------------------|-----------------------------|
|Aginity-Pro-Postgres-Admin-Set1 |Contains common SQL queries to better understand Postgres objects   | 9  |




### The table below details all queries within the [Aginity-Pro-Postgres-Admin-Set1](https://github.com/aginity/Postgres/blob/master/Administrative%20Query%20Packages/Aginity-Pro-Postgres-Admin-Set1.aginitypkg) package.

|Catalog Item Name               |Catalog Item Description            | Required Table     |
|--------------------------|------------------------------------|--------------------|
|Current sessions and their queries  | Shows current user activity    | pg_stat_activity  |
|Databases actual size   | Shows the databases and their actual size   |pg_database   |
|Is autovacuum running   | Is the data autovacuum daemon running right now? |pg_settings   |
|Kill all connections of a current database   | An easy utility to use to kill all open user sessions   |pg_stat_activity   |
|List users   |List all users that have been created in database   | pg_user  |
|Running Queries and Lock Statuses   |Show all running queries and the locks they have created   | pg_stat_activity, pg_locks  |
|Server configuration   |Show key server configuration parameters for the Postgres instance   | N/A uses SHOW ALL command   |
|Unused indexes   | Shows created indexes that are not being referenced   |pg_stat_all_indexes   |
|View Dependency   | Shows a list of tables that a view depends on  | view_tree, view_table_usage  |
