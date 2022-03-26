# uome2

A brief description of what this project does and who it's for

## Tech Stack

**Server:** Node, Express

##

![App Screenshot](https://user-images.githubusercontent.com/7877772/45727888-97f15e80-bc00-11e8-888a-24c190959a8d.jpg)

## Related

Here are of Clean Architecture with Nodejs, TypeScript and Mongo.

[orginal blog post](https://dev.to/japhernandez/clean-architecture-with-nodejs-typescript-and-mongo-3ene)

## project Structure paths

#### Domain

We create the entity with the corresponding attributes like user...that encapsulate Enterprise wide business rules.
And inside Usecase we create the interface that will communicate the domain layer with the infrastructure layer and responsible  for the flow of data to and from the entities, and direct those entities to use their enterprise wide business rules to achieve the goals of the use case..

#### Infrastructure adapter

The software this is aset of adapter that convert data from the format most convenient
for the use cases and entities

#### entry point

Now we create the controller, entry point to the application.
If you name the controller as in the service, it creates code
where you inject the dependency and create the corresponding route.


Steps to run this project:

1. Run `npm watch` command
