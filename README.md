## Overview

## NOTE!

Starting with Jackson 2.2, this module is deprecated.
Use [https://github.com/FasterXML/jackson-jaxrs-providers] instead!

-----

This Jackson extension adds JSON reading/writing support for JAX-RS implementations like [Jersey](http://jersey.java.net/) and [RESTeasy](http://www.jboss.org/resteasy).
This is done by class `JacksonJsonProvider` implementing `javax.ws.rs.ext.MessageBodyReader` and `javax.ws.rs.ext.MessageBodyWriter` that JAX-RS defines for pluggable support for data formats. 
`JacksonJsonProvider` (and `JacksonJaxbJsonProvider`) can then be registered with JAX-RS container to make Jackson the standard JSON reader/writer provider.

## Status

As of Jackson 2.2, this module will be deprecated.
