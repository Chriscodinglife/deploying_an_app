# Week 1

## Intro to MicroServices

Modern software is deplyoed as a service on the internet (SaaS).
The twelve factor app methodology can be implemented to deploying an app

### The Twelve Factor App

1. Always track changes in version control system (VCS) and in a single codebase
2. Dependencies must be explicitly declared
3. Configs should store credentials and third party services. Don't hard code them
4. Other services should be easily accessible via a URL
5. Build Release Run. Build the cold, configure the release, so it can be ready to run
6. Processes should be stateless and share nothing, and persistent data stored centrally
7. Export services via HTTP by binding a service to a port.
8. Concurrency can be used to scale an application and handle increased load
9. Apps should be disposable allowing easy run and killing of services
10. Enable admin processes that can be synced with the app 
11. Apps shouldn't care about logging. Have everything outputted as a stream
12. Have dev match prod environments so that code is consistent

### MicroServices

#### Microservices are:
- An application architecture that takes every function and puts it in its own service 
- Each service runs in a container
- Each service communicates over API's
- Gives teams flexibility on the codebase used for the microservice
- Easily Scalable
- Can iterate over the code easily
- Failures in one service will not impact other services

#### Challenges of creating a monolithic app
- Monolith app is a server-side system based single app, which become highly dependent
- Not scalable
- Specific language or framework
- Making a change can break the codebase

### MicroServices VS Service oriented architecture (SOA)

#### Microservices
Microservices aims to completely decouple services and functions from one another

#### SOA
SOA's make software components reusable via service interfaces
Each service in a SOA has the complete code

### Microservices Do's and Don'ts

#### Do's
- Single Page Applications, which simplifies front-end experience using backing services to update the page dynamically
- BFF Pattern, or Backend For Frontend, which allows the front end call specific microservices
- Strangler Pattern - limit certain functions down to single basic based applications

#### Don'ts
- Don't build microservices until it really needs it, like when the app gets too complex
- Don't use microservices without devops or cloud
- Don't make the microservices way too small
