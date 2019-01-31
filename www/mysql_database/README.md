Command
-------
    >> mysql -u root -p < schema.sql

Problem
-------
for mysql-8.0.14, grant ... on ... to ...@... indetified by ... is not supported. You need break this line into two commands to create and grant separately.
