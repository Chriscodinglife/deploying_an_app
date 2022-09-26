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


