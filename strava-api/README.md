# STRAVA API
###### This project is in development.


If you use IntelliJ IDEA, use Ctrl/Cmd+N to find the `Runner` class. In Eclipse you can use Ctrl/Cmd+Shift+T. When you find it, it’s just a matter of running its main method.

```java
mvn clean package thorntail:run
```

You can also run through a war package:<br>
`java -jar target/rhamt-effort-api-1.0-hollow-thorntail.jar target/rhamt-effort-api-1.0.war`

Check the health of the API:<br>
`curl -s localhost:8080/v1/health/ -i | grep HTTP`

http://localhost:8070/index.html
http://localhost:8070/swagger-ui/
http://localhost:8070/v1/swagger.json

http://www.mastertheboss.com/soa-cloud/openshift/running-microprofile-applications-on-openshift
https://developer.jboss.org/en/jberet/blog/2018/10/01/microservices-batch-application-with-thorntail-and-openshift
https://github.com/jberet/numbers-chunk-thorntail
https://github.com/phillip-kruger/thorntail-jcache-example
https://github.com/thorntail-examples/health-check/blob/master/src/main/java/io/thorntail/example/GreetingResource.java
https://github.com/thorntail-examples/health-check/blob/master/src/main/java/io/thorntail/example/HealthChecks.java
https://github.com/thorntail/thorntail-examples/blob/master/kitchensink-html5-mobile/src/main/java/org/jboss/as/quickstarts/html5_mobile/rest/MemberService.java
https://www.baeldung.com/cdi-event-notification
https://github.com/thorntail/thorntail-examples/blob/master/kitchensink-html5-mobile/src/main/java/org/jboss/as/quickstarts/html5_mobile/data/MemberRepository.java
https://medium.com/@brunodutrafranco_29841/integrated-test-with-arquillian-thorntail-763185a8ce96
https://developer.ibm.com/recipes/tutorials/implementing-microservices-with-thorntail-and-deploying-in-openshift/
https://github.com/debajyoti1d1mukherjee/Thorntail/blob/master/src/main/java/com/poc/thorntail/HealthChecks.java
https://thorntail.io/posts/thorntail-runner/
https://appdev.openshift.io/docs/thorntail-runtime.html
https://stackoverflow.com/questions/27952472/serialize-deserialize-java-8-java-time-with-jackson-json-mapper
https://stackoverflow.com/questions/48868034/cannot-construct-instance-of-java-time-localdate-spring-boot-elasticseach
https://stackoverflow.com/questions/45863678/json-parse-error-can-not-construct-instance-of-java-time-localdate-no-string-a
https://blog.oio.de/2015/06/13/add-support-for-java-8-date-time-api-to-jackson-serialized-rest-web-services/
https://www.baeldung.com/jackson-serialize-dates
https://programmer.group/5c355a95e259a.html
https://kodejava.org/how-to-format-localdate-object-using-jackson/
https://stackoverflow.com/questions/6378526/org-hibernate-persistentobjectexception-detached-entity-passed-to-persist
https://stackoverflow.com/questions/32828778/jpa-persistentobjectexception-detached-entity-passed-to-persist
https://stackoverflow.com/questions/50160778/no-validator-could-be-found-for-constraint-javax-validation-constraints-size
https://www.baeldung.com/hibernate-save-persist-update-merge-saveorupdate