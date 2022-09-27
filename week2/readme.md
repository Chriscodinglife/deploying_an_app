# Serverless Computing

## What is it for?

- Offload infrastrucutre tasks of servers to cloud providers
- Devs can focus more on the code
- There are still servers in serverless computing, just that devs don't manage them
- Code runs on demand, and code scales up 
- End users of serverless do not pay for inactivity

## Pros and Cons of Serverless computing

### Pros
- No instrastructure requirements, so no servers to maintain
- Fault tolerant
- Devs can focus only on coding
- Only pay for what you use

### Cons
- Not ideal for long running processes
- Serverless architectures aren't as portable as containers and vm's
- Devs can get locked in with a certain cloud provider
- Can experience cold starting or the startup of services
- Monitoring can be complex between services, finding faults can be difficult
- Not every language is supported in serverless computing

## FaaS - Function as a Service

- an Event driven computing model where code runs as a response to an event
- Devs can focus on making code as functions
- Functions are stateless
- Application code is packaged as containers
- Faas is a subset of serverless computing
- It is pay per use
- Compatible with microservices

### Pros
- Let's dev focus on code only
- Pay only for what you use
- Provides high availability

## Serverless Stack

- Serverless is not an explicit technology,k it is a set of attributes
- FaaS is an example of a technology that is serverless
- Object storage can handle unstructured data

1. Functions as a Service
2. Serverless databases and Object storage
3. Event streaming and messaging 
4. API Gatways

### Object Storage
- Repositories that have data, metadata and a unique identifier

### API Gateways 
- can expose HTTP routes that can trigger events

## Comparing the FaaS Model

- FaaS can spin up quickly faster than PaaS, Containers and Virtual Machines
- FaaS has no ongoing administration
- Elastic Scaling is an advantage for FaaS
- FaaS does not require capacity planning
- Maintenance is all managed by provided for FaaS
- High availability with no extra cost or effort
- Faas usually vcharges per block of 100 milliseconds

## Serverless Use Cases

### Data Processing

- When a user uploads a picture that a function needs to convert the image to thumbnail

### Massive Parallel computings

- Scale the creation of thumbnails of given images in a storage

### Stream processing workloads

- Iot Sensor data
- Log data
- Financial data
- Fore example a smart speaker at home will trigger a serverless function in the cloud to triger another user requested action

## IBM Cloud Functions

### What are IBM Cloud functions?

- Based on Apache OpenWhisk
- Polyglot (multiple languages
- Access can be granted to a namespace of the cloud function
- One Action can perform one specific task in a given language
- A trigger can enable an action
- Sequences are chains of actions
- Sequences can be invoked via a REST API
- A trigger is a declaration of what you want to react to based on an event
- Rules are set to specifify events to triggers
- A feed can be a webhook or something to feed into triggers
- A Package is a bundle of feeds and actions


### The 8 IBM Cloud functions

1. Namespaces
2. Actions
3. Sequences
4. Events
5. Triggers
6. Rules
7. Feeds
8. Packages

## Definitions

![1]week2defs_Page_1.png
![2]week2defs_Page_2.png
