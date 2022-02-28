# Getting Started

The IM and its dependencies are provided as Dockerized applications.

To start the IM and its dependencies, issue the **up** command:

```shell
docker-compose up -d
```

The IM is now available at [localhost:8666](http://localhost:8666). You can use
the IM UI to edit the possible interventions available for the factory (find out
out to use the UI in the [User Manual](./usermanual.md)). The intervention will
be triggered by the IM and written to the *middleware* component.

Also, Kafka is accessible from the Kafka Development Environment, which is
available at [localhost:3040](http://localhost:3040/). Here you can check
schemas uploaded to the Schema Registry, as well as existing Kafka topics and
their content.
