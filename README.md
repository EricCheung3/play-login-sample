# Play! Login Sample

This is a sample application showing the basic login (authentication/authorization) with Play! 2 for Scala. The sample is based on [Play! 2 Zentasks Sample](https://github.com/playframework/Play20/tree/master/samples/scala/zentasks), but everything except what matters to show authentication and authorization has been removed.

## Setup

It is a default Play! project, thus

* clone the project
* $ play run 

will do the job and you can browse to localhost:9000

## Usage

The application is structured straight forward

* /               default, public index page
* /restricted     restricted content, login will be enforced
* /login          the login form
* /logout         triggers the logout

## Version information

* Play! 2.0.4
* sbt 0.11.3