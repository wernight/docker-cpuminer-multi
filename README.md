Supported tags and respective `Dockerfile` links
================================================

  * [`alpine`, `latest` (Dockerfile)](https://github.com/wernight/docker-cpuminer-multi/blob/master/alpine/Dockerfile) [![](https://images.microbadger.com/badges/image/wernight/cpuminer-multi.svg)](https://microbadger.com/images/wernight/cpuminer-multi "Get your own image badge on microbadger.com")
  * [`debian` (Dockerfile)](https://github.com/wernight/docker-cpuminer-multi/blob/master/debian/Dockerfile) [![](https://images.microbadger.com/badges/image/wernight/cpuminer-multi:debian.svg)](https://microbadger.com/images/wernight/cpuminer-multi:debian "Get your own image badge on microbadger.com")


What is cpuminer-multi
----------------------

[**tpruvot/cpuminer-multi**](https://github.com/tpruvot/cpuminer-multi) is a multi-threaded CPU miner, fork of pooler's [cpuminer](https://github.com/pooler) (see AUTHORS for list of contributors).

It can mine almost all crypto currencies using CPU. This means you're a lot less likely to get a block, so
you might want to join a pool like https://www.multipool.us/dashboard/help/


Usage example
-------------

The `:alpine` tag is smaller but some people reported issue with it.
You can test both `:debian` ([Debian](https://hub.docker.com/_/debian)-based)
and `:alpine` ([Linux Alpine](https://hub.docker.com/_/alpine)-based) versions
to check that they work on your machine via:

    $ docker run --rm wernight/cpuminer-multi:alpine cpuminer --cputest
    $ docker run --rm wernight/cpuminer-multi:alpine cpuminer --benchmark

To see the CLI help do:

    $ docker run --rm wernight/cpuminer-multi cpuminer --help


Feedbacks
---------

This is an **experimental** image. Please report and try to fix any issues you might encounter.

Suggestions are welcome on our [GitHub issue tracker](https://github.com/wernight/docker-cpuminer-multi/issues).
