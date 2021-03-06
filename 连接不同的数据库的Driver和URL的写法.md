### 连接不同的数据库的Driver和URL的写法

- 连接mysql
	- Driver类：`com.mysql.jdbc.Driver`
	- URL：`jdbc:mysql://localhost:3306/test`
- 连接Oracle
	- Driver类：`oracle.jdbc.driver.OracleDriver`
	- URL：`jdbc:oracle:thin:@localhost:1521:[sid]`  
- 连接SQLServer 2000
	- Driver类：`com.microsoft.jdbc.sqlserver.SQLServerDriver`
	- URL：`jdbc:microsoft:sqlserver://localhost:1433;DatabaseName=[database]`
- 连接SQLServer 2005
	- Driver类：`com.microsoft.sqlserver.jdbc.SQLServerDriver`
	- URL：`jdbc:sqlserver://localhost;DatabaseName=[database]`
- 使用JTDs连接SQLServer
	- Driver类：`net.sourceforge.jtds.jdbc.Driver`
	- URL：`jdbc:jtds:sqlserver://localhost:1433/[database];tds=8.0;lastupdatecount=true`
- 连接PostgreSql
	- Driver类：`org.postgresql.Driver`
	- URL：`jdbc:postgresql://localhost/[database]` 
- 连接Sybase
	- Driver类：`com.sybase.jdbc.SybDriver`
	- URL： `jdbc:sybase:Tds:localhost:5007/[database]`
- 连接DB2
	- Driver类：`com.ibm.db2.jdbc.app.DB2Driver`
	- URL: `jdbc:db2://localhost:5000/[database]`
- 连接HsqlDB
	- Driver类：`org.hsqldb.jdbcDriver`
	- URL：`jdbc:hsqldb:mem:generatorDB` 
- 连接Derby 
	- Driver类：`org.apache.derby.jdbc.ClientDriver` 
	- URL:`jdbc:derby://localhost/databaseName`
- 连接H2
	- Driver类：`org.h2.Driver`
	- URL:`jdbc:h2:tcp://localhost/~/test` 