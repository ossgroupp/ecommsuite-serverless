## Micronaut 3.8.3 Documentation

- [User Guide](https://docs.micronaut.io/3.8.3/guide/index.html)
- [API Reference](https://docs.micronaut.io/3.8.3/api/index.html)
- [Configuration Reference](https://docs.micronaut.io/3.8.3/guide/configurationreference.html)
- [Micronaut Guides](https://guides.micronaut.io/index.html)
---

## Handler

[AWS Lambda Handler](https://docs.aws.amazon.com/lambda/latest/dg/java-handler.html)

Handler: com.ltmg.FunctionRequestHandler


## Requisites

- [AWS Account](https://aws.amazon.com/free/)
- [CDK CLI](https://docs.aws.amazon.com/cdk/v2/guide/cli.html)
- [AWS CLI](https://aws.amazon.com/cli/)

## How to deploy

### Generate the deployable artifact

```
./mvnw package
```

### Deploy

The `infra/cdk.json` file tells the CDK Toolkit how to execute your app.

`cd infra`
`cdk synth` - emits the synthesized CloudFormation template
`cdk deploy` - deploy this stack to your default AWS account/region
`cd ..`

Other useful commands:

`cdk diff` - compare deployed stack with current state
`cdk docs`- open CDK documentation

### Cleanup

```
cd infra
cdk destroy
cd ..
```


## Feature netflix-hystrix documentation

- [Micronaut Netflix Hystrix documentation](https://docs.micronaut.io/latest/guide/index.html#netflixHystrix)


## Feature graphql documentation

- [Micronaut GraphQL documentation](https://micronaut-projects.github.io/micronaut-graphql/latest/guide/index.html)


## Feature coherence-data documentation

- [Micronaut Coherence Data documentation](https://micronaut-projects.github.io/micronaut-coherence/latest/guide/#repository)

- [https://coherence.java.net/](https://coherence.java.net/)


## Feature amazon-api-gateway documentation

- [Micronaut Amazon API Gateway REST API documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/index.html#amazonApiGateway)

- [https://docs.aws.amazon.com/apigateway/](https://docs.aws.amazon.com/apigateway/)


## Feature object-storage-aws documentation

- [Micronaut Object Storage - AWS documentation](https://micronaut-projects.github.io/micronaut-object-storage/latest/guide/)

- [https://aws.amazon.com/s3/](https://aws.amazon.com/s3/)


## Feature mongo-sync documentation

- [Micronaut MongoDB Synchronous Driver documentation](https://micronaut-projects.github.io/micronaut-mongodb/latest/guide/index.html)

- [https://docs.mongodb.com](https://docs.mongodb.com)


## Feature multi-tenancy documentation

- [Micronaut Multitenancy documentation](https://docs.micronaut.io/latest/guide/index.html#multitenancy)


## Feature coherence-session documentation

- [Micronaut Coherence HTTP Session Store documentation](https://micronaut-projects.github.io/micronaut-coherence/latest/guide/#coherenceHttpSessions)

- [https://coherence.java.net/](https://coherence.java.net/)


## Feature tracing-opentelemetry-exporter-jaeger documentation

- [Micronaut OpenTelemetry Exporter Jaeger documentation](http://localhost/micronaut-tracing/guide/index.html#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature aws-secrets-manager documentation

- [Micronaut AWS Secrets Manager documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/#distributedconfigurationsecretsmanager)

- [https://aws.amazon.com/secrets-manager/](https://aws.amazon.com/secrets-manager/)


## Feature elasticsearch documentation

- [Micronaut Elasticsearch Driver documentation](https://micronaut-projects.github.io/micronaut-elasticsearch/latest/guide/index.html)


## Feature tracing-opentelemetry-zipkin documentation

- [Micronaut OpenTelemetry Zipkin documentation](https://micronaut-projects.github.io/micronaut-tracing/latest/guide/#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature netflix-ribbon documentation

- [Micronaut Netflix Ribbon LoadBalancer documentation](https://docs.micronaut.io/latest/guide/index.html#netflixRibbon)


## Feature email-amazon-ses documentation

- [Micronaut SES Email documentation](https://micronaut-projects.github.io/micronaut-email/latest/guide/index.html#ses)

- [https://aws.amazon.com/ses/](https://aws.amazon.com/ses/)


## Feature reactor documentation

- [Micronaut Reactor documentation](https://micronaut-projects.github.io/micronaut-reactor/snapshot/guide/index.html)


## Feature serialization-jsonp documentation

- [Micronaut Serialization JSON-B and JSON-P documentation](https://micronaut-projects.github.io/micronaut-serialization/latest/guide/)


## Feature github-workflow-ci documentation

- [https://docs.github.com/en/actions](https://docs.github.com/en/actions)


## Feature serialization-bson documentation

- [Micronaut Serialization BSON documentation](https://micronaut-projects.github.io/micronaut-serialization/latest/guide/)


## Feature aws-parameter-store documentation

- [Micronaut AWS Parameter Store Distributed Configuration documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/index.html#parametersStore)

- [https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html)


## Feature aws-lambda documentation

- [Micronaut AWS Lambda Function documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/index.html#lambda)


## Feature cache-hazelcast documentation

- [Micronaut Hazelcast Cache documentation](https://micronaut-projects.github.io/micronaut-cache/latest/guide/index.html#hazelcast)

- [https://hazelcast.org/](https://hazelcast.org/)


## Feature aws-v2-sdk documentation

- [Micronaut AWS SDK 2.x documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/)

- [https://docs.aws.amazon.com/sdk-for-java/v2/developer-guide/welcome.html](https://docs.aws.amazon.com/sdk-for-java/v2/developer-guide/welcome.html)


## Feature security documentation

- [Micronaut Security documentation](https://micronaut-projects.github.io/micronaut-security/latest/guide/index.html)


## Feature tracing-opentelemetry-exporter-zipkin documentation

- [Micronaut OpenTelemetry Exporter Zipkin documentation](http://localhost/micronaut-tracing/guide/index.html#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature testcontainers documentation

- [https://www.testcontainers.org/](https://www.testcontainers.org/)


## Feature discovery-consul documentation

- [Micronaut Consul Service Discovery documentation](https://docs.micronaut.io/latest/guide/index.html#serviceDiscoveryConsul)

- [https://www.consul.io](https://www.consul.io)


## Feature data-mongodb-reactive documentation

- [Micronaut Data MongoDB Reactive documentation](https://micronaut-projects.github.io/micronaut-data/latest/guide/#mongo)

- [https://docs.mongodb.com](https://docs.mongodb.com)


## Feature kafka documentation

- [Micronaut Kafka Messaging documentation](https://micronaut-projects.github.io/micronaut-kafka/latest/guide/index.html)


## Feature security-oauth2 documentation

- [Micronaut Security OAuth 2.0 documentation](https://micronaut-projects.github.io/micronaut-security/latest/guide/index.html#oauth)


## Feature kafka-streams documentation

- [Micronaut Kafka Streams documentation](https://micronaut-projects.github.io/micronaut-kafka/latest/guide/index.html#kafkaStream)


## Feature config-consul documentation

- [Micronaut Consul Distributed Configuration documentation](https://docs.micronaut.io/latest/guide/index.html#distributedConfigurationConsul)

- [https://www.consul.io](https://www.consul.io)


## Feature security-session documentation

- [Micronaut Security Session documentation](https://micronaut-projects.github.io/micronaut-security/latest/guide/index.html#session)


## Feature security-jwt documentation

- [Micronaut Security JWT documentation](https://micronaut-projects.github.io/micronaut-security/latest/guide/index.html)


## Feature kubernetes-informer documentation

- [Micronaut Kubernetes Informer Support documentation](https://micronaut-projects.github.io/micronaut-kubernetes/latest/guide/#kubernetes-informer)

- [https://github.com/kubernetes-client/java/wiki](https://github.com/kubernetes-client/java/wiki)


## Feature dynamodb documentation

- [Micronaut Amazon DynamoDB documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/#dynamodb)

- [https://aws.amazon.com/dynamodb/](https://aws.amazon.com/dynamodb/)


## Feature coherence-grpc-client documentation

- [Micronaut Coherence gRPC Client documentation](https://micronaut-projects.github.io/micronaut-coherence/latest/guide/#grpc)

- [https://coherence.java.net/](https://coherence.java.net/)


## Feature tracing-opentelemetry-xray documentation

- [Micronaut OpenTelemetry XRay Tracing documentation](https://micronaut-projects.github.io/micronaut-tracing/latest/guide/#opentelemetry)

- [https://docs.aws.amazon.com/xray/latest/devguide/aws-xray.html](https://docs.aws.amazon.com/xray/latest/devguide/aws-xray.html)


## Feature tracing-opentelemetry-jaeger documentation

- [Micronaut OpenTelemetry Jaeger documentation](https://micronaut-projects.github.io/micronaut-tracing/latest/guide/#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature coherence documentation

- [Micronaut Coherence documentation](https://micronaut-projects.github.io/micronaut-coherence/latest/guide/)

- [https://coherence.java.net/](https://coherence.java.net/)


## Feature tracing-opentelemetry documentation

- [Micronaut Integration with OpenTelemetry documentation](https://micronaut-projects.github.io/micronaut-tracing/latest/guide/#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature localstack documentation

- [https://www.testcontainers.org/modules/localstack/](https://www.testcontainers.org/modules/localstack/)


## Feature email-sendgrid documentation

- [Micronaut Sendgrid Email documentation](https://micronaut-projects.github.io/micronaut-email/latest/guide/index.html#sendgrid)

- [https://docs.sendgrid.com/for-developers](https://docs.sendgrid.com/for-developers)


## Feature mqtt documentation

- [Micronaut MQTT v5 Messaging documentation](https://micronaut-projects.github.io/micronaut-mqtt/latest/guide/index.html)


## Feature serialization-jackson documentation

- [Micronaut Serialization Jackson Core documentation](https://micronaut-projects.github.io/micronaut-serialization/latest/guide/)


## Feature jdbc-hikari documentation

- [Micronaut Hikari JDBC Connection Pool documentation](https://micronaut-projects.github.io/micronaut-sql/latest/guide/index.html#jdbc)


## Feature rabbitmq documentation

- [Micronaut RabbitMQ Messaging documentation](https://micronaut-projects.github.io/micronaut-rabbitmq/latest/guide/index.html)


## Feature tracing-opentelemetry-annotations documentation

- [Micronaut OpenTelemetry Annotations documentation](https://micronaut-projects.github.io/micronaut-tracing/latest/guide/#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature hibernate-validator documentation

- [Micronaut Hibernate Validator documentation](https://micronaut-projects.github.io/micronaut-hibernate-validator/latest/guide/index.html)


## Feature tracing-opentelemetry-exporter-otlp documentation

- [Micronaut OpenTelemetry Exporter OTLP documentation](http://localhost/micronaut-tracing/guide/index.html#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature awaitility documentation

- [https://github.com/awaitility/awaitility](https://github.com/awaitility/awaitility)


## Feature mongo-reactive documentation

- [Micronaut MongoDB Reactive Driver documentation](https://micronaut-projects.github.io/micronaut-mongodb/latest/guide/index.html)

- [https://docs.mongodb.com](https://docs.mongodb.com)


## Feature tracing-opentelemetry-exporter-logging documentation

- [Micronaut OpenTelemetry Exporter Logging documentation](http://localhost/micronaut-tracing/guide/index.html#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature flyway documentation

- [Micronaut Flyway Database Migration documentation](https://micronaut-projects.github.io/micronaut-flyway/latest/guide/index.html)

- [https://flywaydb.org/](https://flywaydb.org/)


## Feature kubernetes-reactor-client documentation

- [Micronaut Kubernetes Reactor Client documentation](https://micronaut-projects.github.io/micronaut-kubernetes/latest/guide/#kubernetes-client)

- [https://github.com/kubernetes-client/java/wiki](https://github.com/kubernetes-client/java/wiki)


## Feature aws-cdk documentation

- [https://docs.aws.amazon.com/cdk/v2/guide/home.html](https://docs.aws.amazon.com/cdk/v2/guide/home.html)


## Feature http-client documentation

- [Micronaut HTTP Client documentation](https://docs.micronaut.io/latest/guide/index.html#httpClient)


## Feature mqttv3 documentation

- [Micronaut MQTT v3 Messaging documentation](https://micronaut-projects.github.io/micronaut-mqtt/latest/guide/index.html)


