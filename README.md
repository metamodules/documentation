## Meta-modules

Meta-modules are simple npm modules which include:

- A validated and secure Node.js library
- Metadata for configuring the library (Environment Variables)
- A Docker Container Image which is validated to work with the chosen library
- Metadata for configuring the service's container

For example, the [redis meta-module](https://github.com/metamodules/redis) bundles the [redis](https://github.com/NodeRedis/node_redis) library, a Redis 5 Docker image, and knows how to connect to Redis, _without any configuration!_ Meta-modules wrap some of the complexity of building microservices with Node.js, allowing you to rapidly iterate with the stack of your choice!

Explore modules [here](https://github.com/metamodules) or help create them if the one you want doesn't exist!
