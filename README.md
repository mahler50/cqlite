# Cqlite--a simple implementation of sqlite in c

This is an experimental project tried to explore the fetures of relational database, such as sqlite.

## Fetures

* Pure C implementation
* Data retrieval struct based on B+ Tree
* Support SELECT, INSERT syntax

## How to run

1. complie

    Please use `gcc` to compile the source code since we need some fetures of `gcc` such as `void pointer algorithm` :
    ```
    gcc -o db db.c
    ```

2. run
    ```
    ./db name_of_db_file.db
    ```

3. insert
    Execute `INSERT 1 user user@eamil.com`

4. select
    Execute `select`
    
For more details, please check out `spec/main_spec.rb`, which includes most of the test cases. If you want to execute the test code, please install `ruby lang`.