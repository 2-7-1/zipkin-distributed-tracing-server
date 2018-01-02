# zipkin-distributed-tracing-server
Allows for distributed microservice tracing.  Works with Spring Cloud Sleuth (which assigns a unique ID to each requests.
Java Maven microservice projects need this .pom dependency:
		<dependency>
			<groupId>org.springframework.cloud</groupId>
			<artifactId>spring-cloud-sleuth-zipkin</artifactId>
			<version>2.0.0.M5</version>
		</dependency>
