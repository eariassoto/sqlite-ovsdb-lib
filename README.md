# SQLite SQL-to-OVSDB extension

This SQLite module will create the proper OVSBD RFC calls to communicate to a OVSDB server instance.


## Usage: 

Compile the library:
```bash
sqlite-ovsdb-lib$ mkdir build
sqlite-ovsdb-lib$ cd build
sqlite-ovsdb-lib/build$ cmake ..
sqlite-ovsdb-lib/build$ make
```
Load the extension into sqlite3:
```
sqlite> .load lib/libsqlite-ovsdb-lib.so 
```

## References

+ [SQLite runtime loadable extension](https://www.sqlite.org/loadext.html)
+ [OVSDB RFC documentation](https://tools.ietf.org/html/rfc7047)
