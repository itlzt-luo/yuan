mvn mybatis-generator:generate
mvn flyway:migrate
mvn -Dmybatis.generator.overwrite=true mybatis-generator:generate
