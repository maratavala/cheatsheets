| Description | Command |
| --- | --- |
| List all databases | \l |
| List all tables in current database | \dt |
| List table schema | \d+ <table_name> |
| Switch database | \c <database_name> |
| Export only database schema | pg_dump -h <host_name> -U <user_name> -W -s <database_name> > <export_file_name>.sql |
| Set primary key to 1 (E.g. Table='abc', Key='xyz') | ALTER SEQUENCE abc_xyz_seq RESTART WITH 1; |
