# Enhanced Snakes and Ladders
## Dependencies
- This project requires the MySQL Connector/J to connect to a MySQL database.
- You can download the connector from the [MySQL website](https://dev.mysql.com/downloads/connector/j/).
- Include the `.jar` file as a dependency:
  - Add it to the Java `CLASSPATH` or specify it in the `-classpath` or `-cp` option (as shown).
  - Add it to your `pom.xml` file if you're using Maven.
  - Add it to your `build.gradle` file if you're using Gradle.
## How to play
- Clone this repository.
- Compile and run the `Start.java` file in `src/`.
```bash
$ export CLASSPATH=.:/path/to/mysql-connector-j-8.4.0.jar
$ cd src/
$ javac Start.java
$ java Start
```
or
```bash
$ cd src/
$ javac Start.java
$ java Start -cp .:/path/to/mysql-connector-j-8.4.0.jar
```
On Windows, replace `export` with `set` and `:` with `;`.
