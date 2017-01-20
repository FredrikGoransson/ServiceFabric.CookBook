# ServiceFabric CookBook

## Contents

* Service Fabric architecture
  * Microservices architecture
    * Domain Driven Design
      * AgregateRoots
      * Bounded Contexts
    * Scaling and performance considerations
  * Designing Services
    * Stateful Services
    * Stateless Services
  * Designing Actors
  * Service and Actor communication
  * Service state and persistance
    * Reliability
    * Backup / restore
    * Search across multiple states
    * External storage
      * Document DB
      * SQL Server
* Development Guidelines
  * Service base class
    * ``ServiceProxyFactory``
    * ``ActorProxyFactory``
    * ``ApplicationUriBuilder``
  * Exception and Error handling
    * Internal Service/Actor exceptions
    * Client exception handling
      * Retries
    * Fabric exceptions
    * Logging
  * Testing and development process
    * Dependency injection in Services and Actors
    * Mock objects
    * Integration tests with ``MockFabricRuntime`` a.k.a. ``FabricMocktime``
    
    
