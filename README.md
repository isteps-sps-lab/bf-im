# Intervention Manager (IM)

The *im* component allows users to easily define intervention rules to
orchestrate a production system. The component monitors the status of the
worker-factory ecosystem in real-time, by elaborating data from sensors,
machines, workers monitoring systems, ERP, and more. The set of intervention
rules are known to the *im*, which decides which is the best one to trigger.

## Getting Started

The IM and its dependencies are provided as Dockerized applications.

To start the IM and its dependencies, issue the **up** command:

```shell
docker-compose up -d
```

The IM is now available at [localhost:8666](http://localhost:8666). You can use
the IM UI to edit the possible interventions available for the factory (find out
how to use the UI in the [User Manual](./usermanual.md)). The intervention will
be triggered by the IM and written to the *middleware* component.

Also, Kafka is accessible from the Kafka Development Environment, which is
available at [localhost:3040](http://localhost:3040/). Here you can check
schemas uploaded to the Schema Registry, as well as existing Kafka topics and
their content.

## Software Details

* Documentation: https://isteps-sps-lab.github.io/bf-im/

## Maintainers

- Vincenzo Cutrona - <vincenzo.cutrona@supsi.ch>
- Niko Bonomi - <niko.bonomi@supsi.ch>
- Giuseppe Landolfi - <giuseppe.landolfi@supsi.ch>

## Acknowledgement

H2020 Innovation Action -- This project has received funding from the
European Union's Horizon 2020 research and innovation programme under
grant agreement No 951813.
