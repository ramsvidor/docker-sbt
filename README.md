# Scala and sbt for Docker
[![](https://images.microbadger.com/badges/image/ramsvidor/sbt.svg)](https://microbadger.com/images/ramsvidor/sbt "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/ramsvidor/sbt.svg)](http://microbadger.com/images/ramsvidor/sbt "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/commit/ramsvidor/sbt.svg)](http://microbadger.com/images/ramsvidor/sbt "Get your own commit badge on microbadger.com")
[![](https://images.microbadger.com/badges/license/ramsvidor/sbt.svg)](http://microbadger.com/images/ramsvidor/sbt "Get your own license badge on microbadger.com")

Image for building and running sbt and Scala projects.

**@see** [Dockerfile](https://github.com/ramsvidor/docker-sbt/blob/develop/Dockerfile)

## Base image
* [ramsvidor/graalvm](https://hub.docker.com/r/ramsvidor/graalvm) (GraalVM 22.0.0 / JDK 17 / Debian 11 - bullseye-slim variant)

## JRE and JDK included - for production, see how to build native images
This image is intended to run and build [Scala](http://www.scala-lang.org) and [sbt](http://www.scala-sbt.org) 
applications in a development environment. If you're looking for running in a production environment you should consider
using a [GraalVM native image](https://www.graalvm.org/docs/reference-manual/native-image).

## Supported Docker versions
This image is officially supported on Docker version 20.10 and newer.
Support for older versions is provided on a best-effort basis.
Please see the [Docker installation documentation](https://docs.docker.com/install/) for details on how to upgrade your 
Docker daemon.

## Contributing
You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull 
requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a 
[GitHub issue](https://github.com/ramsvidor/docker-sbt/issues), especially for more ambitious contributions. This 
gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you 
find out if someone else is working on the same thing.

## License
This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").
