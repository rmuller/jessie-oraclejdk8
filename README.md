README
======

[Docker](https://www.docker.com/what-docker) repository for the automated build of a compact image 
with **Debian 8** ("Jessie"), **Maven 3** and (a size optimized) **Oracle JDK 8**.

`rmuller/jessie-oraclejdk8` is based on a trimmed down Debian 8 base image (`debian:jessie-slim`,
which is about 35% smaller than `debian:jessy`) and has the Oracle JDK 8 installed.

Total size of this image is 247 MB.

This image is available via [hub.docker.com](https://hub.docker.com/r/rmuller/jessie-oraclejdk8/).

| Docker tag | Debian 8   | Oracle JDK 8 | Maven 3  |
|------------|------------|--------------|----------|
| 1.0.0      | 8.6        | 1.8.0_112    | 3.3.9    |

To run this image in interactive mode:

```` bash
$ docker run -it rmuller/jessie-oraclejdk8
````

