# UserManagement



"C:\Program Files\Java\jdk-17\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2025.1.2\lib\idea_rt.jar=53114" -Dfile.encoding=UTF-8 -classpath D:\Workspace\API\UserManagement\target\classes;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter-data-jpa\3.5.3\spring-boot-starter-data-jpa-3.5.3.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter\3.5.3\spring-boot-starter-3.5.3.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot\3.5.3\spring-boot-3.5.3.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-autoconfigure\3.5.3\spring-boot-autoconfigure-3.5.3.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter-logging\3.5.3\spring-boot-starter-logging-3.5.3.jar;C:\Users\Siddharth\.m2\repository\ch\qos\logback\logback-classic\1.5.18\logback-classic-1.5.18.jar;C:\Users\Siddharth\.m2\repository\ch\qos\logback\logback-core\1.5.18\logback-core-1.5.18.jar;C:\Users\Siddharth\.m2\repository\org\apache\logging\log4j\log4j-to-slf4j\2.24.3\log4j-to-slf4j-2.24.3.jar;C:\Users\Siddharth\.m2\repository\org\apache\logging\log4j\log4j-api\2.24.3\log4j-api-2.24.3.jar;C:\Users\Siddharth\.m2\repository\org\slf4j\jul-to-slf4j\2.0.17\jul-to-slf4j-2.0.17.jar;C:\Users\Siddharth\.m2\repository\jakarta\annotation\jakarta.annotation-api\2.1.1\jakarta.annotation-api-2.1.1.jar;C:\Users\Siddharth\.m2\repository\org\yaml\snakeyaml\2.4\snakeyaml-2.4.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter-jdbc\3.5.3\spring-boot-starter-jdbc-3.5.3.jar;C:\Users\Siddharth\.m2\repository\com\zaxxer\HikariCP\6.3.0\HikariCP-6.3.0.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-jdbc\6.2.8\spring-jdbc-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\hibernate\orm\hibernate-core\6.6.18.Final\hibernate-core-6.6.18.Final.jar;C:\Users\Siddharth\.m2\repository\jakarta\persistence\jakarta.persistence-api\3.1.0\jakarta.persistence-api-3.1.0.jar;C:\Users\Siddharth\.m2\repository\jakarta\transaction\jakarta.transaction-api\2.0.1\jakarta.transaction-api-2.0.1.jar;C:\Users\Siddharth\.m2\repository\org\jboss\logging\jboss-logging\3.6.1.Final\jboss-logging-3.6.1.Final.jar;C:\Users\Siddharth\.m2\repository\org\hibernate\common\hibernate-commons-annotations\7.0.3.Final\hibernate-commons-annotations-7.0.3.Final.jar;C:\Users\Siddharth\.m2\repository\io\smallrye\jandex\3.2.0\jandex-3.2.0.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\classmate\1.7.0\classmate-1.7.0.jar;C:\Users\Siddharth\.m2\repository\net\bytebuddy\byte-buddy\1.17.6\byte-buddy-1.17.6.jar;C:\Users\Siddharth\.m2\repository\org\glassfish\jaxb\jaxb-runtime\4.0.5\jaxb-runtime-4.0.5.jar;C:\Users\Siddharth\.m2\repository\org\glassfish\jaxb\jaxb-core\4.0.5\jaxb-core-4.0.5.jar;C:\Users\Siddharth\.m2\repository\org\eclipse\angus\angus-activation\2.0.2\angus-activation-2.0.2.jar;C:\Users\Siddharth\.m2\repository\org\glassfish\jaxb\txw2\4.0.5\txw2-4.0.5.jar;C:\Users\Siddharth\.m2\repository\com\sun\istack\istack-commons-runtime\4.1.2\istack-commons-runtime-4.1.2.jar;C:\Users\Siddharth\.m2\repository\jakarta\inject\jakarta.inject-api\2.0.1\jakarta.inject-api-2.0.1.jar;C:\Users\Siddharth\.m2\repository\org\antlr\antlr4-runtime\4.13.0\antlr4-runtime-4.13.0.jar;C:\Users\Siddharth\.m2\repository\org\springframework\data\spring-data-jpa\3.5.1\spring-data-jpa-3.5.1.jar;C:\Users\Siddharth\.m2\repository\org\springframework\data\spring-data-commons\3.5.1\spring-data-commons-3.5.1.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-orm\6.2.8\spring-orm-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-context\6.2.8\spring-context-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-aop\6.2.8\spring-aop-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-tx\6.2.8\spring-tx-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-beans\6.2.8\spring-beans-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\slf4j\slf4j-api\2.0.17\slf4j-api-2.0.17.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-aspects\6.2.8\spring-aspects-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\aspectj\aspectjweaver\1.9.24\aspectjweaver-1.9.24.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter-web\3.5.3\spring-boot-starter-web-3.5.3.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter-json\3.5.3\spring-boot-starter-json-3.5.3.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\jackson\core\jackson-databind\2.19.1\jackson-databind-2.19.1.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\jackson\core\jackson-annotations\2.19.1\jackson-annotations-2.19.1.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\jackson\core\jackson-core\2.19.1\jackson-core-2.19.1.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\jackson\datatype\jackson-datatype-jdk8\2.19.1\jackson-datatype-jdk8-2.19.1.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\jackson\datatype\jackson-datatype-jsr310\2.19.1\jackson-datatype-jsr310-2.19.1.jar;C:\Users\Siddharth\.m2\repository\com\fasterxml\jackson\module\jackson-module-parameter-names\2.19.1\jackson-module-parameter-names-2.19.1.jar;C:\Users\Siddharth\.m2\repository\org\springframework\boot\spring-boot-starter-tomcat\3.5.3\spring-boot-starter-tomcat-3.5.3.jar;C:\Users\Siddharth\.m2\repository\org\apache\tomcat\embed\tomcat-embed-core\10.1.42\tomcat-embed-core-10.1.42.jar;C:\Users\Siddharth\.m2\repository\org\apache\tomcat\embed\tomcat-embed-el\10.1.42\tomcat-embed-el-10.1.42.jar;C:\Users\Siddharth\.m2\repository\org\apache\tomcat\embed\tomcat-embed-websocket\10.1.42\tomcat-embed-websocket-10.1.42.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-web\6.2.8\spring-web-6.2.8.jar;C:\Users\Siddharth\.m2\repository\io\micrometer\micrometer-observation\1.15.1\micrometer-observation-1.15.1.jar;C:\Users\Siddharth\.m2\repository\io\micrometer\micrometer-commons\1.15.1\micrometer-commons-1.15.1.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-webmvc\6.2.8\spring-webmvc-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-expression\6.2.8\spring-expression-6.2.8.jar;C:\Users\Siddharth\.m2\repository\com\mysql\mysql-connector-j\8.2.0\mysql-connector-j-8.2.0.jar;C:\Users\Siddharth\.m2\repository\org\projectlombok\lombok\1.18.38\lombok-1.18.38.jar;C:\Users\Siddharth\.m2\repository\jakarta\xml\bind\jakarta.xml.bind-api\4.0.2\jakarta.xml.bind-api-4.0.2.jar;C:\Users\Siddharth\.m2\repository\jakarta\activation\jakarta.activation-api\2.1.3\jakarta.activation-api-2.1.3.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-core\6.2.8\spring-core-6.2.8.jar;C:\Users\Siddharth\.m2\repository\org\springframework\spring-jcl\6.2.8\spring-jcl-6.2.8.jar com.example.user_management.UserManagementApplication

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/

 :: Spring Boot ::                (v3.5.3)

2025-06-24T20:17:17.727+01:00  INFO 18888 --- [user_management] [           main] c.e.u.UserManagementApplication          : Starting UserManagementApplication using Java 17.0.12 with PID 18888 (D:\Workspace\API\UserManagement\target\classes started by Siddharth in D:\Workspace\API\UserManagement)
2025-06-24T20:17:17.734+01:00  INFO 18888 --- [user_management] [           main] c.e.u.UserManagementApplication          : No active profile set, falling back to 1 default profile: "default"
2025-06-24T20:17:18.720+01:00  INFO 18888 --- [user_management] [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data JPA repositories in DEFAULT mode.
2025-06-24T20:17:18.813+01:00  INFO 18888 --- [user_management] [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 79 ms. Found 1 JPA repository interface.
2025-06-24T20:17:19.507+01:00  INFO 18888 --- [user_management] [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port 8080 (http)
2025-06-24T20:17:19.530+01:00  INFO 18888 --- [user_management] [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2025-06-24T20:17:19.531+01:00  INFO 18888 --- [user_management] [           main] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.42]
2025-06-24T20:17:19.597+01:00  INFO 18888 --- [user_management] [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2025-06-24T20:17:19.598+01:00  INFO 18888 --- [user_management] [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1773 ms
2025-06-24T20:17:19.841+01:00  INFO 18888 --- [user_management] [           main] o.hibernate.jpa.internal.util.LogHelper  : HHH000204: Processing PersistenceUnitInfo [name: default]
2025-06-24T20:17:19.935+01:00  INFO 18888 --- [user_management] [           main] org.hibernate.Version                    : HHH000412: Hibernate ORM core version 6.6.18.Final
2025-06-24T20:17:19.993+01:00  INFO 18888 --- [user_management] [           main] o.h.c.internal.RegionFactoryInitiator    : HHH000026: Second-level cache disabled
2025-06-24T20:17:20.366+01:00  INFO 18888 --- [user_management] [           main] o.s.o.j.p.SpringPersistenceUnitInfo      : No LoadTimeWeaver setup: ignoring JPA class transformer
2025-06-24T20:17:20.399+01:00  INFO 18888 --- [user_management] [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2025-06-24T20:17:20.768+01:00  INFO 18888 --- [user_management] [           main] com.zaxxer.hikari.pool.HikariPool        : HikariPool-1 - Added connection com.mysql.cj.jdbc.ConnectionImpl@56b9d43f
2025-06-24T20:17:20.770+01:00  INFO 18888 --- [user_management] [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Start completed.
2025-06-24T20:17:20.845+01:00  WARN 18888 --- [user_management] [           main] org.hibernate.orm.deprecation            : HHH90000025: MySQLDialect does not need to be specified explicitly using 'hibernate.dialect' (remove the property setting and it will be selected by default)
2025-06-24T20:17:20.886+01:00  INFO 18888 --- [user_management] [           main] org.hibernate.orm.connections.pooling    : HHH10001005: Database info:
	Database JDBC URL [Connecting through datasource 'HikariDataSource (HikariPool-1)']
	Database driver: undefined/unknown
	Database version: 8.0.36
	Autocommit mode: undefined/unknown
	Isolation level: undefined/unknown
	Minimum pool size: undefined/unknown
	Maximum pool size: undefined/unknown
2025-06-24T20:17:20.902+01:00 DEBUG 18888 --- [user_management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(12, org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@6248cfab) replaced previous registration(org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@5871a482)
2025-06-24T20:17:20.902+01:00 DEBUG 18888 --- [user_management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(-9, org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@45c90a05) replaced previous registration(org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@296676c4)
2025-06-24T20:17:20.902+01:00 DEBUG 18888 --- [user_management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(-3, org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@df7d1d4) replaced previous registration(org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@58f7215c)
2025-06-24T20:17:20.903+01:00 DEBUG 18888 --- [user_management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(4003, org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@55638165) replaced previous registration(org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@4fa91d5b)
2025-06-24T20:17:20.903+01:00 DEBUG 18888 --- [user_management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(4001, org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@7ce30c0b) replaced previous registration(org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@1d7f2f0a)
2025-06-24T20:17:20.903+01:00 DEBUG 18888 --- [user_management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(4002, org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@54defd69) replaced previous registration(org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@531a716c)
2025-06-24T20:17:20.903+01:00 DEBUG 18888 --- [user_management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(2004, org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@377dbc50) replaced previous registration(org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@531ec2ca)
2025-06-24T20:17:20.903+01:00 DEBUG 18888 --- [user_management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(2005, org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@70884875) replaced previous registration(org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@7019d619)
2025-06-24T20:17:20.904+01:00 DEBUG 18888 --- [user_management] [           main] o.h.t.d.sql.spi.DdlTypeRegistry          : addDescriptor(2011, org.hibernate.type.descriptor.sql.internal.CapacityDependentDdlType@2a5c6b76) replaced previous registration(org.hibernate.type.descriptor.sql.internal.DdlTypeImpl@ff1f465)
2025-06-24T20:17:21.938+01:00  INFO 18888 --- [user_management] [           main] o.h.e.t.j.p.i.JtaPlatformInitiator       : HHH000489: No JTA platform available (set 'hibernate.transaction.jta.platform' to enable JTA platform integration)
Hibernate: 
    create table users (
        id bigint not null auto_increment,
        email varchar(255) not null,
        first_name varchar(255) not null,
        last_name varchar(255) not null,
        primary key (id)
    ) engine=InnoDB
Hibernate: 
    alter table users 
       drop index UK6dotkott2kjsp8vw4d0m25fb7
Hibernate: 
    alter table users 
       add constraint UK6dotkott2kjsp8vw4d0m25fb7 unique (email)
2025-06-24T20:17:22.097+01:00  INFO 18888 --- [user_management] [           main] j.LocalContainerEntityManagerFactoryBean : Initialized JPA EntityManagerFactory for persistence unit 'default'
2025-06-24T20:17:22.431+01:00  WARN 18888 --- [user_management] [           main] JpaBaseConfiguration$JpaWebConfiguration : spring.jpa.open-in-view is enabled by default. Therefore, database queries may be performed during view rendering. Explicitly configure spring.jpa.open-in-view to disable this warning
2025-06-24T20:17:22.924+01:00  WARN 18888 --- [user_management] [           main] ConfigServletWebServerApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.context.ApplicationContextException: Failed to start bean 'webServerStartStop'
2025-06-24T20:17:22.925+01:00  INFO 18888 --- [user_management] [           main] j.LocalContainerEntityManagerFactoryBean : Closing JPA EntityManagerFactory for persistence unit 'default'
2025-06-24T20:17:22.927+01:00  INFO 18888 --- [user_management] [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Shutdown initiated...
2025-06-24T20:17:22.939+01:00  INFO 18888 --- [user_management] [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Shutdown completed.
2025-06-24T20:17:22.954+01:00  INFO 18888 --- [user_management] [           main] .s.b.a.l.ConditionEvaluationReportLogger : 

Error starting ApplicationContext. To display the condition evaluation report re-run your application with 'debug' enabled.
2025-06-24T20:17:22.977+01:00 ERROR 18888 --- [user_management] [           main] o.s.b.d.LoggingFailureAnalysisReporter   : 

***************************
APPLICATION FAILED TO START
***************************

Description:

Web server failed to start. Port 8080 was already in use.

Action:

Identify and stop the process that's listening on port 8080 or configure this application to listen on another port.


Process finished with exit code 1
