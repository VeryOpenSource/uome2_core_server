# uome2

A brief description of what this project does and who it's for

## Tech Stack

**Client:** Flutter, bloc,

**Server:** Node, Express

## Sample of Clean Architecture

![App Screenshot](https://user-images.githubusercontent.com/7877772/45727888-97f15e80-bc00-11e8-888a-24c190959a8d.jpg)

## Related

Here are of Clean Architecture with Nodejs, TypeScript and Mongo.

[orginal blog post](https://dev.to/japhernandez/clean-architecture-with-nodejs-typescript-and-mongo-3ene)

## project Structure paths

#### Domain

Inside Model Folder We create the entity with the corresponding attributes like user...
And inside Usecase we create the interface that will communicate the domain layer with the infrastructure layer.
we are also create the service that is going to have all the logic to store the user

#### Infrastructure

Inside adapter there is mongoose Folder and We create the model with the attributes of
the entity that is in the domain, ensuring that the entries are the same.At this point the implementation of
the interface in the adapter helps us with the communication between the layers

#### entry point

Now we create the controller, entry point to the application.
If you name the controller as in the service, it creates code
where you inject the dependency and create the corresponding route.
When creating the service the name that we gave him was add-user,
we must use that same name for the controller.

Steps to run this project:

1. Run `npm watch` command
