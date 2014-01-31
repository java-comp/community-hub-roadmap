# Server Structure

The server is to be limited to exposing the application data as a REST service.

## Technologies
The following technologies should be applied:
1. REST interface,
2. Reactive backend,
3. Implemented using the Play framework,
4. Implemented using the Scala language.

## Scope
The scope of the server is strictly limited to implementing the REST contract 
as defined in the api descriptor, defined in RAML.

## Capabilities
The server should implement the capabilities as defined in the api descriptor.
Additionally, the server should allow integrations.

### Integration
Users should be able to use the application to interact with (other) social 
networks. They should have the option to (re)publish their activities. 
Additionally an event may have reference in a social network. The server 
should, as reasonably as possible, ensure the event attendance of the 
application is reflected in the social network.