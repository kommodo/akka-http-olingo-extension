akka-http-olingo-extension
==========================

- A simple project showing how `ODATA 4.0 services` can be developed using `akka-http` and `Apache Olingo`.

- `akka-http` is a lite framework for developing REST applications in Scala. `Apache Olingo` is a framework which allows implementing Rest services with OData 4.0. 

- The `example` directory contains the sample Olingo project. 

- The class `OdataAkkaHttpHandlerImpl` is extended to integrate Apache Olingo and akka-http. The best of both frameworks can be used now.

compatibility
=============

compatible with olingo >= 4.0.0

testing
=======

- start the application with `sbt:run`

- open `http://localhost:8080`. The odata service page opens up.

- open `http://localhost:8080/$metadata`. The metadata page shows up.

- open `http://localhost:8080/Dummies`. The entity with dummy data shows up.