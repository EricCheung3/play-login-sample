# Play! Login Sample

This is a sample application showing the basic login (authentication/authorization) with Play! 2 for Scala. The sample is based on [Play! 2 Zentasks Sample](https://github.com/playframework/Play20/tree/master/samples/scala/zentasks), but everything except what matters to show authentication and authorization has been removed.

## Setup

It is a default Play! project, thus

* clone the project
* $ play run 

will do the job and you can browse to localhost:9000

## Usage

The application is structured straight forward

<table>
  <tr>
    <td>/</td>
    <td>default, public index page</td>
  </tr>
  <tr>
    <td>/restricted</td>
    <td>restricted content, login will be enforced</td>
  </tr>
  <tr>
    <td>/login</td>
    <td>the login form</td>
  </tr>
  <tr>
    <td>/logout</td>
    <td>triggers the logout</td>
  </tr>
</table>

## Version information

* Play! 2.0.4
* sbt 0.11.3