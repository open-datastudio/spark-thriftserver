# Spark thriftserver

Spark thriftserver

  - Allows JDBC/ODBC clients to execute SQL queries over JDBC and ODBC protocols on Apache Spark. 
  - Spark cluster running on Kubernetes that powers SQL queries.
  - Spark UI access.
  - Integrated with [hive-metastore](https://github.com/open-datastudio/hive-metastore).
  - One click deployment on [staroid](https://staroid.com).
  
[![Run](https://staroid.com/api/run/button.svg)](https://staroid.com/api/run)


## Development

Run locally with [skaffold](https://skaffold.dev) command.

```
$ skaffold dev --port-forward -p minikube
```
