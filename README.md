psql  -U oini
oini=# \l  >> list databases

oini=# create user vector with encrypted password 'vector';
CREATE ROLE
oini=# grant SELECT on pg_stat_database to vector;
GRANT
oini=# grant SELECT on pg_stat_database_conflicts to vector;
GRANT
oini=# grant SELECT on pg_stat_bgwriter to vector;
GRANT
