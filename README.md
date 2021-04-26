# How to evaluate Ontop

1. Modify [testcases/config-postgresql.ini](test-cases/config-postgresql.ini) or [testcases/config-mysql.ini](test-cases/config-mysql.ini) to config Ontop
2. Stop MySQL or PostgreSQL on your local machine (if any)
3. Run the tests

```shell
$ cd r2rml-test-cases-support
$ python3 -m pip install -r requirements.txt
$ python3 test.py ../config-postgresql.ini
$ python3 test.py ../config-mysql.ini
```
