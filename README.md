## Info

> this repo contains configuration files for microservices to distribute with consul as config service, check this repo : https://github.com/ubmagh/microservice-architecture-consul-with-spring


> Each service receives a configuration by a profile dev/prod, and default configuration that contains common configuration of the two profiles. In addition it receives the global configuration (application.properties)

> configuration is hot loaded, as we use actuator (calling POST:/actuator/refresh ) on the microservices after we push the new configuration in this repo.

> 