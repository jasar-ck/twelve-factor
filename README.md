# twelve-factor


This the common approach to build a large scale project on cloud.

Background : https://12factor.net/

###1. code base

One code base per app  -> Application for dev and stage code stored in the git repo

###2. dependencies

Explicitly declared the dependencies and isolate the dependencies.
Here pom.xml is used to declare the dependencies.

###3. config

store config in the environment.
spring cloud configuration - To implement this feature in large scale application

###4. Backing Service

Treat backing service as attached resources

###5. Backing Service

Treat backing service as attached resources

###6. Processes

Execute the apps as one or more stateless processes

###7. Port Binding

Export service as port binding

###8. Concurrency

Scale out via the process model

###9. Disposibility
MAximize robustness with fast start up and graceful shutdown

###10. Environmental Parity
Keep all environments are similar as possible

###11. Logging
Treat Logs as a stream service

###12. Admin Process
Run Admin tasks as one of process


