## Unit Tests
   *Validate the methods and classes defined in a test behave as expected
   *Can run at every build
   *doesnot require a network connection

## Integration Tests
 * Test your service from the client's perspective
 * 2 flavors
   ** Dependency integration tests located in service package
   ** Remote Integration tests locataed in a separate test package
 * Integration tests generally require a fully deployed stack to run
 * Synonymous with e2e testing, blackbox testing, system testing , user-scenario testing, regression testing

## Canary Testing
 * Continous and frequent tests running against your prod environment mimicking customer actions. They
   attempt to catch deployment failures

## Load Tests
 * Identify the limits of your product ( TPS, number of connections)
 * Stress Tests are a variation of load tests will test a service beyond its normal operational capacity
 * Performance Tests measure the speed and responsiveness of a system
