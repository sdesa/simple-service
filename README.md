# simple-service

This is a simple microservice that has the following dependencies:

**config-client**<br>
**service-registry**

The service can be deployed to cloud foundry as long as there is a service registry and a config server available (see **manifest.yml** for details).

Note that the service does not need a config server or service registry when running locally.
