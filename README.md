# docker-nodejs-examples

Some basic examples of using Node.js and Docker.

You can run these directly with Docker or use Vagrant. 

Follow [the developer on Twitter](https://twitter.com/ashleydavis75) for updates on his new book Bootstrapping Microservices.

Need to do exploratory coding, data analysis and visulalization in JavaScript/TypeScript? [Check out Data-Forge Notebook](http://www.data-forge-notebook.com/)

## Setup

To use Vagrant you need Vagrant and Virtual Box installed, then open a terminal, change into the repository's directory and run:

    vagrant up

That will give you Linux VM with Docker installed that you can use to run the examples.

Please see the README in each sub-directory for more instructions.

## Simplest example

The `simple` sub-directory contains the simplest example of Node.js and Docker.

## Multi-stage build 

The `multi` sub-directory shows an example of multi-stage Docker build that compiles TypeScript code.