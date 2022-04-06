# MultiServiceTaskPetProject
The first attempt to build a project with microservices.


This pet-project an attempt to build an application using a micro service architecture.

The web api (drf, and swagger documentation) is used to interact with the client side.
A message broker (Rabbitmq) is used for the interaction of all services.
Sqlite is used as a database (there will be a migration to postgresql in the future).

The main idea is to create abstract tasks that will be executed asynchronously by the corresponding executors.

At the first stage, a couple of services (a common template) and a web api + a small client application using this api.
