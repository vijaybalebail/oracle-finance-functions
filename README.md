# oracle-finance-functions
This is a attempt to collaborate and create financial functions in oracle PLSQL using the recommended method and can be used in Financial application development, rest APIs , microservices or simple sql queries.


- all functions could be in a package or as individual functions.
- all function are do not call other custom functions within it. This reduced interdependencies.
- all functions should be deterministic.
- all function using pipelined and Table functions should be parallel enabled.
