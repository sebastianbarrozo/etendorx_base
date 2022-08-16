# etendorx_base

* Configure the Etendo RX project

``` groovy
./gradlew setup --info
```


* Edit the 'das.yaml' and 'gradle.properties' file pointing to an existing database

``` groovy
spring:
  datasource:
    url: jdbc:postgresql://localhost:5432/etendo
```

* Generate the entities
```groovy 
./gradlew generate.entities --info
```

* Start the services

``` groovy
./gradlew rx --info
```

