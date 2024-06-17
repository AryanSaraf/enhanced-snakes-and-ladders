# Enhanced Snakes and Ladders
## Dependencies
- This project requires the MySQL Connector/J to connect to a MySQL database.
- You can download the connector from the [MySQL website](https://dev.mysql.com/downloads/connector/j/).
## How to play
- Clone this repository.
- Compile and run the `Start.java` file in `src/`.
```bash
export CLASSPATH=.:/path/to/mysql-connector-j-8.4.0.jar
cd src/
javac Start.java
java Start
```
or
```bash
cd src/
javac Start.java
java Start -cp .:/path/to/mysql-connector-j-8.4.0.jar
```
On Windows, replace the `:` with `;`.
