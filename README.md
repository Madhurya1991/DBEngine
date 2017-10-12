# DBEngine

The goal of this project is to implement a (very) rudimentary database engine that is loosely based on MySQL, 
which is called DavisBase. Implementation should operate entirely from the command line (no GUI).

Supported Commands
------------------

Supports the following high-level commands. All commands should be terminated by a semicolon (;).
• SHOW SCHEMAS – Displays all schemas defined in your database.
• USE – Chooses a schema.
• SHOW TABLES – Displays all tables in the currently chosen schema.
• CREATE SCHEMA – Creates a new schema to hold tables.
• CREATE TABLE – Creates a new table schema, i.e. a new empty table.
• INSERT INTO TABLE – Inserts a row/record into a table.
• DROP TABLE – Remove a table schema, and all of its contained data.
• “SELECT-FROM-WHERE” -style query
• EXIT – Cleanly exits the program and saves all table and index information in non-volatile files.
