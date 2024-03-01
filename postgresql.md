# PostgreSQL

## Select Activity For User

`select pid, application_name, query from pg_stat_activity where usename = 'master';`

## Select Activity For Process ID

`select * from pg_catalog.pg_stat_activity where pid = 12051;`

## Cancel Process ID

`select pg_cancel_backend(28136);`

## Terminate Process ID

`select pg_terminate_backend(28136);`
