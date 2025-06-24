# UserManagement



"C:\Program Files\Java\jdk-17\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2025.1.2\lib\idea_rt.jar=52998" -Dfile.encoding=UTF-8 -classpath D:\Workspace\API\UserManagement\target\classes;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter-data-jpa\3.5.3\spring-boot-starter-data-jpa-3.5.3.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter\3.5.3\spring-boot-starter-3.5.3.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot\3.5.3\spring-boot-3.5.3.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-autoconfigure\3.5.3\spring-boot-autoconfigure-3.5.3.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter-logging\3.5.3\spring-boot-starter-logging-3.5.3.jar;C:\Users\Siddharth\.m2\repository\ch\qos\logback\logback-classic\1.5.18\logback-classic-1.5.18.jar;C:\Users\Siddharth\.m2\repository\ch\qos\logback\logback-core\1.5.18\logback-core-1.5.18.jar;C:\Users\Siddharth\.m2\repository\org\apache\logging\log4j\log4j-to-slf4j\2.24.3\log4j-to-slf4j-2.24.3.jar;C:\Users\Siddharth\.m2\repository\org\apache\logging\log4j\log4j-api\2.24.3\log4j-api-2.24.3.jar;C:\Users\Siddharth\.m2\repository\org\slf4j\jul-to-slf4j\2.0.17\jul-to-slf4j-2.0.17.jar;C:\Users\Siddharth\.m2\repository\jakarta\annotation\jakarta.annotation-api\2.1.1\jakarta.annotation-api-2.1.1.jar;C:\Users\Siddharth\.m2\repository\org\yaml\snakeyaml\2.4\snakeyaml-2.4.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter-jdbc\3.5.3\spring-boot-starter-jdbc-3.5.3.jar;C:\Users\Siddharth\.m2\repository\com\zaxxer\HikariCP\6.3.0\HikariCP-6.3.0.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-jdbc\6.2.8\spring-jdbc-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\hibernate\orm\hibernate-core\6.6.18.Final\hibernate-core-6.6.18.Final.jar;C:\Users\Siddharth\.m2\repository\jakarta\persistence\jakarta.persistence-api\3.1.0\jakarta.persistence-api-3.1.0.jar;C:\Users\Siddharth\.m2\repository\jakarta\transaction\jakarta.transaction-api\2.0.1\jakarta.transaction-api-2.0.1.jar;C:\Users\Siddharth\.m2\repository\org\jboss\logging\jboss-logging\3.6.1.Final\jboss-logging-3.6.1.Final.jar;C:\Users\Siddharth\.m2\repository\org\hibernate\common\hibernate-commons-annotations\7.0.3.Final\hibernate-commons-annotations-7.0.3.Final.jar;C:\Users\Siddharth\.m2\repository\io\smallrye\jandex\3.2.0\jandex-3.2.0.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\classmate\1.7.0\classmate-1.7.0.jar;C:\Users\Siddharth\.m2\repository\net\bytebuddy\byte-buddy\1.17.6\byte-buddy-1.17.6.jar;C:\Users\Siddharth\.m2\repository\org\glassfish\jaxb\jaxb-runtime\4.0.5\jaxb-runtime-4.0.5.jar;C:\Users\Siddharth\.m2\repository\org\glassfish\jaxb\jaxb-core\4.0.5\jaxb-core-4.0.5.jar;C:\Users\Siddharth\.m2\repository\org\eclipse\angus\angus-activation\2.0.2\angus-activation-2.0.2.jar;C:\Users\Siddharth\.m2\repository\org\glassfish\jaxb\txw2\4.0.5\txw2-4.0.5.jar;C:\Users\Siddharth\.m2\repository\com\sun\istack\istack-commons-runtime\4.1.2\istack-commons-runtime-4.1.2.jar;C:\Users\Siddharth\.m2\repository\jakarta\inject\jakarta.inject-api\2.0.1\jakarta.inject-api-2.0.1.jar;C:\Users\Siddharth\.m2\repository\org\antlr\antlr4-runtime\4.13.0\antlr4-runtime-4.13.0.jar;C:\Users\Siddharth\.m2\repository\org\springframework\data\spring-data-jpa\3.5.1\spring-data-jpa-3.5.1.jar;C:\Users\Siddharth\.m2\repository\org\springframework\data\spring-data-commons\3.5.1\spring-data-commons-3.5.1.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-orm\6.2.8\spring-orm-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-context\6.2.8\spring-context-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-aop\6.2.8\spring-aop-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-tx\6.2.8\spring-tx-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-beans\6.2.8\spring-beans-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\slf4j\slf4j-api\2.0.17\slf4j-api-2.0.17.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-aspects\6.2.8\spring-aspects-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\aspectj\aspectjweaver\1.9.24\aspectjweaver-1.9.24.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter-web\3.5.3\spring-boot-starter-web-3.5.3.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter-json\3.5.3\spring-boot-starter-json-3.5.3.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\jackson\core\jackson-databind\2.19.1\jackson-databind-2.19.1.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\jackson\core\jackson-annotations\2.19.1\jackson-annotations-2.19.1.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\jackson\core\jackson-core\2.19.1\jackson-core-2.19.1.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\jackson\datatype\jackson-datatype-jdk8\2.19.1\jackson-datatype-jdk8-2.19.1.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\jackson\datatype\jackson-datatype-jsr310\2.19.1\jackson-datatype-jsr310-2.19.1.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\jackson\module\jackson-module-parameter-names\2.19.1\jackson-module-parameter-names-2.19.1.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter-tomcat\3.5.3\spring-boot-starter-tomcat-3.5.3.jar;C:\Users\Siddharth\.m2\repository\org\apache\tomcat\embed\tomcat-embed-core\10.1.42\tomcat-embed-core-10.1.42.jar;C:\Users\Siddharth\.m2\repository\org\apache\tomcat\embed\tomcat-embed-el\10.1.42\tomcat-embed-el-10.1.42.jar;C:\Users\Siddharth\.m2\repository\org\apache\tomcat\embed\tomcat-embed-websocket\10.1.42\tomcat-embed-websocket-10.1.42.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-web\6.2.8\spring-web-6.2.8.jar;C:\Users\Siddharth\.m2\repository\io\micrometer\micrometer-observation\1.15.1\micrometer-observation-1.15.1.jar;C:\Users\Siddharth\.m2\repository\io\micrometer\micrometer-commons\1.15.1\micrometer-commons-1.15.1.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-webmvc\6.2.8\spring-webmvc-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-expression\6.2.8\spring-expression-6.2.8.jar;C:\Users\Siddharth\.m2\repository\com\mysql\mysql-connector-j\8.2.0\mysql-connector-j-8.2.0.jar;C:\Users\Siddharth\.m2\repository\org\projectlombok\lombok\1.18.38\lombok-1.18.38.jar;C:\Users\Siddharth\.m2\repository\jakarta\xml\bind\jakarta.xml.bind-api\4.0.2\jakarta.xml.bind-api-4.0.2.jar;C:\Users\Siddharth\.m2\repository\jakarta\activation\jakarta.activation-api\2.1.3\jakarta.activation-api-2.1.3.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-core\6.2.8\spring-core-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-jcl\6.2.8\spring-jcl-6.2.8.jar com.example.user_management.UserManagementApplication

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/

 :: Spring Boot ::                (v3.5.3)

2025-06-24T20:11:26.386+01:00  INFO 7660 --- [user-management] [           main] c.e.u.UserManagementApplication          : Starting UserManagementApplication using Java 17.0.12 with PID 7660 (D:\Workspace\API\UserManagement\target\classes started by Siddharth in D:\Workspace\API\UserManagement)
2025-06-24T20:11:26.391+01:00  INFO 7660 --- [user-management] [           main] c.e.u.UserManagementApplication          : No active profile set, falling back to 1 default profile: "default"
2025-06-24T20:11:27.511+01:00  INFO 7660 --- [user-management] [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data JPA repositories in DEFAULT mode.
2025-06-24T20:11:27.624+01:00  INFO 7660 --- [user-management] [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 97 ms. Found 1 JPA repository interface.
2025-06-24T20:11:28.451+01:00  INFO 7660 --- [user-management] [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port 8080 (http)
2025-06-24T20:11:28.470+01:00  INFO 7660 --- [user-management] [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2025-06-24T20:11:28.471+01:00  INFO 7660 --- [user-management] [           main] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.42]
2025-06-24T20:11:28.574+01:00  INFO 7660 --- [user-management] [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2025-06-24T20:11:28.576+01:00  INFO 7660 --- [user-management] [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 2105 ms
2025-06-24T20:11:28.849+01:00  INFO 7660 --- [user-management] [           main] o.hibernate.jpa.internal.util.LogHelper  : HHH000204: Processing PersistenceUnitInfo [name: default]
2025-06-24T20:11:28.917+01:00  INFO 7660 --- [user-management] [           main] org.hibernate.Version                    : HHH000412: Hibernate ORM core version 6.6.18.Final
2025-06-24T20:11:28.970+01:00  INFO 7660 --- [user-management] [           main] o.h.c.internal.RegionFactoryInitiator    : HHH000026: Second-level cache disabled
2025-06-24T20:11:29.435+01:00  INFO 7660 --- [user-management] [           main] o.s.o.j.p.SpringPersistenceUnitInfo      : No LoadTimeWeaver setup: ignoring JPA class transformer
2025-06-24T20:11:29.479+01:00  INFO 7660 --- [user-management] [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2025-06-24T20:11:30.899+01:00  WARN 7660 --- [user-management] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Error: 1049, SQLState: 42000
2025-06-24T20:11:30.899+01:00 ERROR 7660 --- [user-management] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : Unknown database 'user-management'
2025-06-24T20:11:30.900+01:00  WARN 7660 --- [user-management] [           main] o.h.e.j.e.i.JdbcEnvironmentInitiator     : HHH000342: Could not obtain connection to query metadata

org.hibernate.exception.SQLGrammarException: unable to obtain isolated JDBC connection [Unknown database 'user-management'] [n/a]
	at org.hibernate.exception.internal.SQLStateConversionDelegate.convert(SQLStateConversionDelegate.java:91) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.exception.internal.StandardSQLExceptionConverter.convert(StandardSQLExceptionConverter.java:58) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.engine.jdbc.spi.SqlExceptionHelper.convert(SqlExceptionHelper.java:108) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.engine.jdbc.spi.SqlExceptionHelper.convert(SqlExceptionHelper.java:94) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.resource.transaction.backend.jdbc.internal.JdbcIsolationDelegate.delegateWork(JdbcIsolationDelegate.java:116) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.engine.jdbc.env.internal.JdbcEnvironmentInitiator.getJdbcEnvironmentUsingJdbcMetadata(JdbcEnvironmentInitiator.java:336) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.engine.jdbc.env.internal.JdbcEnvironmentInitiator.initiateService(JdbcEnvironmentInitiator.java:129) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.engine.jdbc.env.internal.JdbcEnvironmentInitiator.initiateService(JdbcEnvironmentInitiator.java:81) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.boot.registry.internal.StandardServiceRegistryImpl.initiateService(StandardServiceRegistryImpl.java:130) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.service.internal.AbstractServiceRegistryImpl.createService(AbstractServiceRegistryImpl.java:263) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.service.internal.AbstractServiceRegistryImpl.initializeService(AbstractServiceRegistryImpl.java:238) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.service.internal.AbstractServiceRegistryImpl.getService(AbstractServiceRegistryImpl.java:215) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.boot.model.relational.Database.<init>(Database.java:45) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.boot.internal.InFlightMetadataCollectorImpl.getDatabase(InFlightMetadataCollectorImpl.java:226) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.boot.internal.InFlightMetadataCollectorImpl.<init>(InFlightMetadataCollectorImpl.java:194) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.boot.model.process.spi.MetadataBuildingProcess.complete(MetadataBuildingProcess.java:171) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.jpa.boot.internal.EntityManagerFactoryBuilderImpl.metadata(EntityManagerFactoryBuilderImpl.java:1442) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.jpa.boot.internal.EntityManagerFactoryBuilderImpl.build(EntityManagerFactoryBuilderImpl.java:1513) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.springframework.orm.jpa.vendor.SpringHibernateJpaPersistenceProvider.createContainerEntityManagerFactory(SpringHibernateJpaPersistenceProvider.java:66) ~[spring-orm-6.2.8.jar:6.2.8]
	at org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean.createNativeEntityManagerFactory(LocalContainerEntityManagerFactoryBean.java:390) ~[spring-orm-6.2.8.jar:6.2.8]
	at org.springframework.orm.jpa.AbstractEntityManagerFactoryBean.buildNativeEntityManagerFactory(AbstractEntityManagerFactoryBean.java:419) ~[spring-orm-6.2.8.jar:6.2.8]
	at org.springframework.orm.jpa.AbstractEntityManagerFactoryBean.afterPropertiesSet(AbstractEntityManagerFactoryBean.java:400) ~[spring-orm-6.2.8.jar:6.2.8]
	at org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean.afterPropertiesSet(LocalContainerEntityManagerFactoryBean.java:366) ~[spring-orm-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.invokeInitMethods(AbstractAutowireCapableBeanFactory.java:1873) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.initializeBean(AbstractAutowireCapableBeanFactory.java:1822) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:607) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:529) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:339) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:373) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:337) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:207) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.context.support.AbstractApplicationContext.finishBeanFactoryInitialization(AbstractApplicationContext.java:970) ~[spring-context-6.2.8.jar:6.2.8]
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:627) ~[spring-context-6.2.8.jar:6.2.8]
	at org.springframework.boot.web.servlet.context.ServletWebServerApplicationContext.refresh(ServletWebServerApplicationContext.java:146) ~[spring-boot-3.5.3.jar:3.5.3]
	at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:752) ~[spring-boot-3.5.3.jar:3.5.3]
	at org.springframework.boot.SpringApplication.refreshContext(SpringApplication.java:439) ~[spring-boot-3.5.3.jar:3.5.3]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:318) ~[spring-boot-3.5.3.jar:3.5.3]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1361) ~[spring-boot-3.5.3.jar:3.5.3]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1350) ~[spring-boot-3.5.3.jar:3.5.3]
	at com.example.user_management.UserManagementApplication.main(UserManagementApplication.java:10) ~[classes/:na]
Caused by: java.sql.SQLSyntaxErrorException: Unknown database 'user-management'
	at com.mysql.cj.jdbc.exceptions.SQLError.createSQLException(SQLError.java:121) ~[mysql-connector-j-8.2.0.jar:8.2.0]
	at com.mysql.cj.jdbc.exceptions.SQLExceptionsMapping.translateException(SQLExceptionsMapping.java:122) ~[mysql-connector-j-8.2.0.jar:8.2.0]
	at com.mysql.cj.jdbc.ConnectionImpl.createNewIO(ConnectionImpl.java:815) ~[mysql-connector-j-8.2.0.jar:8.2.0]
	at com.mysql.cj.jdbc.ConnectionImpl.<init>(ConnectionImpl.java:438) ~[mysql-connector-j-8.2.0.jar:8.2.0]
	at com.mysql.cj.jdbc.ConnectionImpl.getInstance(ConnectionImpl.java:241) ~[mysql-connector-j-8.2.0.jar:8.2.0]
	at com.mysql.cj.jdbc.NonRegisteringDriver.connect(NonRegisteringDriver.java:189) ~[mysql-connector-j-8.2.0.jar:8.2.0]
	at com.zaxxer.hikari.util.DriverDataSource.getConnection(DriverDataSource.java:139) ~[HikariCP-6.3.0.jar:na]
	at com.zaxxer.hikari.pool.PoolBase.newConnection(PoolBase.java:368) ~[HikariCP-6.3.0.jar:na]
	at com.zaxxer.hikari.pool.PoolBase.newPoolEntry(PoolBase.java:205) ~[HikariCP-6.3.0.jar:na]
	at com.zaxxer.hikari.pool.HikariPool.createPoolEntry(HikariPool.java:483) ~[HikariCP-6.3.0.jar:na]
	at com.zaxxer.hikari.pool.HikariPool.checkFailFast(HikariPool.java:571) ~[HikariCP-6.3.0.jar:na]
	at com.zaxxer.hikari.pool.HikariPool.<init>(HikariPool.java:101) ~[HikariCP-6.3.0.jar:na]
	at com.zaxxer.hikari.HikariDataSource.getConnection(HikariDataSource.java:111) ~[HikariCP-6.3.0.jar:na]
	at org.hibernate.engine.jdbc.connections.internal.DatasourceConnectionProviderImpl.getConnection(DatasourceConnectionProviderImpl.java:126) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.engine.jdbc.env.internal.JdbcEnvironmentInitiator$ConnectionProviderJdbcConnectionAccess.obtainConnection(JdbcEnvironmentInitiator.java:483) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.resource.transaction.backend.jdbc.internal.JdbcIsolationDelegate.delegateWork(JdbcIsolationDelegate.java:61) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	... 35 common frames omitted

2025-06-24T20:11:30.925+01:00  WARN 7660 --- [user-management] [           main] org.hibernate.orm.deprecation            : HHH90000025: MySQLDialect does not need to be specified explicitly using 'hibernate.dialect' (remove the property setting and it will be selected by default)
2025-06-24T20:11:30.943+01:00  INFO 7660 --- [user-management] [           main] org.hibernate.orm.connections.pooling    : HHH10001005: Database info:
	Database JDBC URL [Connecting through datasource 'HikariDataSource (null)']
	Database driver: undefined/unknown
	Database version: 8.0
	Autocommit mode: undefined/unknown
	Isolation level: undefined/unknown
	Minimum pool size: undefined/unknown
	Maximum pool size: undefined/unknown
2025-06-24T20:11:30.956+01:00 DEBUG 7660 --- [user-management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(12, org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@4403bff8) replaced previous registration(org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@261275ae)
2025-06-24T20:11:30.957+01:00 DEBUG 7660 --- [user-management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(-9, org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@502c087e) replaced previous registration(org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@49986178)
2025-06-24T20:11:30.957+01:00 DEBUG 7660 --- [user-management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(-3, org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@10bdfbcc) replaced previous registration(org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@25b74370)
2025-06-24T20:11:30.957+01:00 DEBUG 7660 --- [user-management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(4003, org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@15e8c040) replaced previous registration(org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@1f71e024)
2025-06-24T20:11:30.957+01:00 DEBUG 7660 --- [user-management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(4001, org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@60ed0b9d) replaced previous registration(org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@7f5e6833)
2025-06-24T20:11:30.957+01:00 DEBUG 7660 --- [user-management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(4002, org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@2c674d58) replaced previous registration(org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@3c07e830)
2025-06-24T20:11:30.958+01:00 DEBUG 7660 --- [user-management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(2004, org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@34beadce) replaced previous registration(org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@382d549a)
2025-06-24T20:11:30.958+01:00 DEBUG 7660 --- [user-management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(2005, org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@2eb6d34a) replaced previous registration(org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@2d73e8c4)
2025-06-24T20:11:30.959+01:00 DEBUG 7660 --- [user-management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(2011, org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@260d48f5) replaced previous registration(org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@148ab138)
2025-06-24T20:11:31.863+01:00  INFO 7660 --- [user-management] [           main] o.h.e.t.j.p.i.JtaPlatformInitiator       : HHH000489: No JTA platform available (set 'hibernate.transaction.jta.platform' to enable JTA platform integration)
2025-06-24T20:11:31.885+01:00  INFO 7660 --- [user-management] [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2025-06-24T20:11:32.923+01:00  WARN 7660 --- [user-management] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : SQL Error: 1049, SQLState: 42000
2025-06-24T20:11:32.923+01:00 ERROR 7660 --- [user-management] [           main] o.h.engine.jdbc.spi.SqlExceptionHelper   : Unknown database 'user-management'
2025-06-24T20:11:32.929+01:00 ERROR 7660 --- [user-management] [           main] j.LocalContainerEntityManagerFactoryBean : Failed to initialize JPA EntityManagerFactory: [PersistenceUnit: default] Unable to build Hibernate SessionFactory; nested exception is org.hibernate.exception.SQLGrammarException: Unable to open JDBC Connection for DDL execution [Unknown database 'user-management'] [n/a]
2025-06-24T20:11:32.931+01:00  WARN 7660 --- [user-management] [           main] ConfigServletWebServerApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'entityManagerFactory' defined in class path resource [org/springframework/boot/autoconfigure/orm/jpa/HibernateJpaConfiguration.class]: [PersistenceUnit: default] Unable to build Hibernate SessionFactory; nested exception is org.hibernate.exception.SQLGrammarException: Unable to open JDBC Connection for DDL execution [Unknown database 'user-management'] [n/a]
2025-06-24T20:11:32.936+01:00  INFO 7660 --- [user-management] [           main] o.apache.catalina.core.StandardService   : Stopping service [Tomcat]
2025-06-24T20:11:32.950+01:00  INFO 7660 --- [user-management] [           main] .s.b.a.l.ConditionEvaluationReportLogger : 

Error starting ApplicationContext. To display the condition evaluation report re-run your application with 'debug' enabled.
2025-06-24T20:11:32.974+01:00 ERROR 7660 --- [user-management] [           main] o.s.boot.SpringApplication               : Application run failed

org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'entityManagerFactory' defined in class path resource [org/springframework/boot/autoconfigure/orm/jpa/HibernateJpaConfiguration.class]: [PersistenceUnit: default] Unable to build Hibernate SessionFactory; nested exception is org.hibernate.exception.SQLGrammarException: Unable to open JDBC Connection for DDL execution [Unknown database 'user-management'] [n/a]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.initializeBean(AbstractAutowireCapableBeanFactory.java:1826) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:607) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:529) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:339) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:373) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:337) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:207) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.context.support.AbstractApplicationContext.finishBeanFactoryInitialization(AbstractApplicationContext.java:970) ~[spring-context-6.2.8.jar:6.2.8]
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:627) ~[spring-context-6.2.8.jar:6.2.8]
	at org.springframework.boot.web.servlet.context.ServletWebServerApplicationContext.refresh(ServletWebServerApplicationContext.java:146) ~[spring-boot-3.5.3.jar:3.5.3]
	at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:752) ~[spring-boot-3.5.3.jar:3.5.3]
	at org.springframework.boot.SpringApplication.refreshContext(SpringApplication.java:439) ~[spring-boot-3.5.3.jar:3.5.3]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:318) ~[spring-boot-3.5.3.jar:3.5.3]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1361) ~[spring-boot-3.5.3.jar:3.5.3]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1350) ~[spring-boot-3.5.3.jar:3.5.3]
	at com.example.user_management.UserManagementApplication.main(UserManagementApplication.java:10) ~[classes/:na]
Caused by: jakarta.persistence.PersistenceException: [PersistenceUnit: default] Unable to build Hibernate SessionFactory; nested exception is org.hibernate.exception.SQLGrammarException: Unable to open JDBC Connection for DDL execution [Unknown database 'user-management'] [n/a]
	at org.springframework.orm.jpa.AbstractEntityManagerFactoryBean.buildNativeEntityManagerFactory(AbstractEntityManagerFactoryBean.java:431) ~[spring-orm-6.2.8.jar:6.2.8]
	at org.springframework.orm.jpa.AbstractEntityManagerFactoryBean.afterPropertiesSet(AbstractEntityManagerFactoryBean.java:400) ~[spring-orm-6.2.8.jar:6.2.8]
	at org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean.afterPropertiesSet(LocalContainerEntityManagerFactoryBean.java:366) ~[spring-orm-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.invokeInitMethods(AbstractAutowireCapableBeanFactory.java:1873) ~[spring-beans-6.2.8.jar:6.2.8]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.initializeBean(AbstractAutowireCapableBeanFactory.java:1822) ~[spring-beans-6.2.8.jar:6.2.8]
	... 15 common frames omitted
Caused by: org.hibernate.exception.SQLGrammarException: Unable to open JDBC Connection for DDL execution [Unknown database 'user-management'] [n/a]
	at org.hibernate.exception.internal.SQLExceptionTypeDelegate.convert(SQLExceptionTypeDelegate.java:66) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.exception.internal.StandardSQLExceptionConverter.convert(StandardSQLExceptionConverter.java:58) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.engine.jdbc.spi.SqlExceptionHelper.convert(SqlExceptionHelper.java:108) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.engine.jdbc.spi.SqlExceptionHelper.convert(SqlExceptionHelper.java:94) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.resource.transaction.backend.jdbc.internal.DdlTransactionIsolatorNonJtaImpl.getIsolatedConnection(DdlTransactionIsolatorNonJtaImpl.java:74) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.resource.transaction.backend.jdbc.internal.DdlTransactionIsolatorNonJtaImpl.getIsolatedConnection(DdlTransactionIsolatorNonJtaImpl.java:39) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.tool.schema.internal.exec.ImprovedExtractionContextImpl.getJdbcConnection(ImprovedExtractionContextImpl.java:63) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.tool.schema.internal.exec.ImprovedExtractionContextImpl.getJdbcDatabaseMetaData(ImprovedExtractionContextImpl.java:70) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.tool.schema.extract.internal.InformationExtractorJdbcDatabaseMetaDataImpl.processTableResultSet(InformationExtractorJdbcDatabaseMetaDataImpl.java:65) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.tool.schema.extract.internal.AbstractInformationExtractorImpl.getTables(AbstractInformationExtractorImpl.java:570) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.tool.schema.extract.internal.DatabaseInformationImpl.getTablesInformation(DatabaseInformationImpl.java:122) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.tool.schema.internal.GroupedSchemaMigratorImpl.performTablesMigration(GroupedSchemaMigratorImpl.java:72) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.tool.schema.internal.AbstractSchemaMigrator.performMigration(AbstractSchemaMigrator.java:233) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.tool.schema.internal.AbstractSchemaMigrator.doMigration(AbstractSchemaMigrator.java:112) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.tool.schema.spi.SchemaManagementToolCoordinator.performDatabaseAction(SchemaManagementToolCoordinator.java:280) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.tool.schema.spi.SchemaManagementToolCoordinator.lambda$process$5(SchemaManagementToolCoordinator.java:144) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at java.base/java.util.HashMap.forEach(HashMap.java:1421) ~[na:na]
	at org.hibernate.tool.schema.spi.SchemaManagementToolCoordinator.process(SchemaManagementToolCoordinator.java:141) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.boot.internal.SessionFactoryObserverForSchemaExport.sessionFactoryCreated(SessionFactoryObserverForSchemaExport.java:37) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.internal.SessionFactoryObserverChain.sessionFactoryCreated(SessionFactoryObserverChain.java:35) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.internal.SessionFactoryImpl.<init>(SessionFactoryImpl.java:324) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.boot.internal.SessionFactoryBuilderImpl.build(SessionFactoryBuilderImpl.java:463) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.jpa.boot.internal.EntityManagerFactoryBuilderImpl.build(EntityManagerFactoryBuilderImpl.java:1517) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.springframework.orm.jpa.vendor.SpringHibernateJpaPersistenceProvider.createContainerEntityManagerFactory(SpringHibernateJpaPersistenceProvider.java:66) ~[spring-orm-6.2.8.jar:6.2.8]
	at org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean.createNativeEntityManagerFactory(LocalContainerEntityManagerFactoryBean.java:390) ~[spring-orm-6.2.8.jar:6.2.8]
	at org.springframework.orm.jpa.AbstractEntityManagerFactoryBean.buildNativeEntityManagerFactory(AbstractEntityManagerFactoryBean.java:419) ~[spring-orm-6.2.8.jar:6.2.8]
	... 19 common frames omitted
Caused by: java.sql.SQLSyntaxErrorException: Unknown database 'user-management'
	at com.mysql.cj.jdbc.exceptions.SQLError.createSQLException(SQLError.java:121) ~[mysql-connector-j-8.2.0.jar:8.2.0]
	at com.mysql.cj.jdbc.exceptions.SQLExceptionsMapping.translateException(SQLExceptionsMapping.java:122) ~[mysql-connector-j-8.2.0.jar:8.2.0]
	at com.mysql.cj.jdbc.ConnectionImpl.createNewIO(ConnectionImpl.java:815) ~[mysql-connector-j-8.2.0.jar:8.2.0]
	at com.mysql.cj.jdbc.ConnectionImpl.<init>(ConnectionImpl.java:438) ~[mysql-connector-j-8.2.0.jar:8.2.0]
	at com.mysql.cj.jdbc.ConnectionImpl.getInstance(ConnectionImpl.java:241) ~[mysql-connector-j-8.2.0.jar:8.2.0]
	at com.mysql.cj.jdbc.NonRegisteringDriver.connect(NonRegisteringDriver.java:189) ~[mysql-connector-j-8.2.0.jar:8.2.0]
	at com.zaxxer.hikari.util.DriverDataSource.getConnection(DriverDataSource.java:139) ~[HikariCP-6.3.0.jar:na]
	at com.zaxxer.hikari.pool.PoolBase.newConnection(PoolBase.java:368) ~[HikariCP-6.3.0.jar:na]
	at com.zaxxer.hikari.pool.PoolBase.newPoolEntry(PoolBase.java:205) ~[HikariCP-6.3.0.jar:na]
	at com.zaxxer.hikari.pool.HikariPool.createPoolEntry(HikariPool.java:483) ~[HikariCP-6.3.0.jar:na]
	at com.zaxxer.hikari.pool.HikariPool.checkFailFast(HikariPool.java:571) ~[HikariCP-6.3.0.jar:na]
	at com.zaxxer.hikari.pool.HikariPool.<init>(HikariPool.java:101) ~[HikariCP-6.3.0.jar:na]
	at com.zaxxer.hikari.HikariDataSource.getConnection(HikariDataSource.java:111) ~[HikariCP-6.3.0.jar:na]
	at org.hibernate.engine.jdbc.connections.internal.DatasourceConnectionProviderImpl.getConnection(DatasourceConnectionProviderImpl.java:126) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.engine.jdbc.env.internal.JdbcEnvironmentInitiator$ConnectionProviderJdbcConnectionAccess.obtainConnection(JdbcEnvironmentInitiator.java:483) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	at org.hibernate.resource.transaction.backend.jdbc.internal.DdlTransactionIsolatorNonJtaImpl.getIsolatedConnection(DdlTransactionIsolatorNonJtaImpl.java:46) ~[hibernate-core-6.6.18.Final.jar:6.6.18.Final]
	... 40 common frames omitted


Process finished with exit code 1
