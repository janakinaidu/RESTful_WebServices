# RESTful_WebServices

 Jersey provides it’s own API that extend the JAX-RS toolkit with additional features and utilities to further simplify RESTful service and client development.
 
i)Jersey:
			Jersey is the reference implementation provided by Sun. For using Jersey as our JAX-RS implementation, all we need 	to configure its servlet in web.xml and add required dependencies. Note that JAX-RS API is part of JDK not Jersey, so we have to add its dependency jars in our application.

ii)RESTEasy:RESTEasy is the JBoss project that provides JAX-RS implementation

->REST is an architectural style for developing applications that can be accessed over the network.
->Restful Web Services is a stateless client-server architecture where web services are resources and 
  can be identified by their URIs.
  
->REST doesn’t specify any specific protocol to use
->but in almost all cases it’s used over HTTP/HTTPS

Java RESTful Web Services API
=============================
->Java API for RESTful Web Services (JAX-RS) is the Java API for creating REST web services.
->JAX-RS uses annotations to simplify the development and deployment of web services
->JAX-RS is part of JDK, so you don’t need to include anything to use it’s annotations.


Two Major Implementations:
==========================
i)Jersey:Jersey is the reference implementation provided by Sun. For using Jersey as our JAX-RS implementation, all we need to configure its servlet in web.xml and add required dependencies.
Note that JAX-RS API is part of JDK not Jersey, so we have to add its dependency jars in our application

ii)RESTEasy: RESTEasy is the JBoss project that provides JAX-RS implementation.


Concept of Serilization and De-serilization:
--------------------------------------------
	->Serialization and Deserialization in Java. Serialization is a process of converting an object into a 
	  sequence of bytes which can be persisted to a disk or database or can be sent through streams.
	->The reverse process of creating object from sequence of bytes is called deserialization.

//source:
https://www.journaldev.com/9170/restful-web-services-tutorial-java
