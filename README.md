# rabbitmq-multicontainer-cluster

Creates a RabbitMQ cluster on docker that is build on top of 3 containers. It is standalone and is a good take for DEV and test environments.

These nodes cannot be joined to other clusters because of the same epmd port they are using.

A HA proxy is used for single entry connection. Singled nodes can be stopped within containers.
