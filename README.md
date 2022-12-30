# DropWizard


Creating a new DropWizard Project with Maven
---

```bash
mvn archetype:generate -B -DarchetypeGroupId=io.dropwizard.archetypes -DarchetypeArtifactId=java-simple -DarchetypeVersion=2.1.4  -DgroupId=com.pranaybathini  -DartifactId=dropwizard-starter -Dversion=1.0-SNAPSHOT -Dpackage=com.pranaybathini  -Dname=DropWizard
```

How to start the DropWizard application
---

1. Run `mvn clean install` to build your application
1. Start application with `java -jar target/dropwizard-starter-1.0-SNAPSHOT.jar server config.yml`
1. To check that your application is running enter url `http://localhost:8080`

Health Check
---

To see your applications health enter url `http://localhost:8081/healthcheck`
