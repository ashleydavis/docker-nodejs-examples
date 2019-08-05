# docker-nodejs-examples

Some basic examples of using Node.js and Docker.

You can run these directly with Docker or use Vagrant. 

To use Vagrant you need Vagrant and Virtual Box installed, then in this direct run

    vagrant up

That will give you Linux VM with Docker installed that you can use to run the examples.

Please see the README in each sub-directory for more instructions.

## Simplest example

The `simple` sub-directory contains the simplest example of Node.js and Docker.

## Multi-stage build 

The `multi` sub-directory shows an example of multi-stage Docker build that compiles TypeScript code.