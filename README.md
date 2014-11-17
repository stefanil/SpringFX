#SpringFX

##Server
This module encapsulates an embedded Jetty server for exposing a RESTful interface using Apache CXF's implementation of JAX-RS. The prescribed technmologies are glued together using the Spring Framework.   

###Getting Started
In Eclipse simply run `org.devel.springfx.server.Starter` as Java application.

###Technology Stack
* (embedded) Jetty
* Spring
* Apache CXF (JAX-RS)

##Client
A simple demo client for accessing the serverside REST-API.

###Getting Started
In Eclipse simply run `org.devel.springfx.client.Starter` as Java application.

###Technology Stack
* Apache CXF Client Proxy

##Further Documentation
* http://aredko.blogspot.de/2013/01/going-rest-embedding-jetty-with-spring.html
* http://cxf.apache.org/docs/jax-rs-client-api.html
* http://cxf.apache.org/docs/jax-rs.html
