Served at https://trangmei.github.io/cc-schema/

To generate your own ERD

Get Schemaspy: https://github.com/schemaspy/schemaspy/releases

Get latest MySQL JDBC driver: https://dev.mysql.com/downloads/connector/j/

Command line: `java -jar schemaspy-6.0.0.jar -dp <path to>/mysql-connector-java-5.1.47.jar -t mysql -host localhost -db carecorner_rails_development -u <your DB user> -o ./cc-schema -s carecorner_rails_development`
