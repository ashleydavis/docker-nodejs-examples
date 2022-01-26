# Multi-stage Docker build example

A more complicated Node.js and Docker example that has a multi-stage build.

This includes a build process for compiling TypeScript files to JavaScript.

## Files

- multi/
  - src/index.ts      Example Express web server in TypeScript.
  - .dockerignore     Make Docker ignore specified files.
  - Dockerfile        Script file for building our Docker image.
  - package.json      Node.js package file, specifies npm dependencies.
  - tsconfig.json     Configuration file for the TypeScript compiler.

## Setup

You need Node.js and Docker installed.

First change to the directory and install dependencies:

```bash
cd multi
npm install
```

## Directly run

Before running the Node.js application you must build the TypeScripot code:

```bash
npm run build
```

Now, run it directly like this:

```bash
npm start
```

## Build and run using Docker

To build the Docker image:

```bash
npm run docker:build
```

To run the Docker image:

```bash
npm run docker:run
```

To see what Docker images you have locally:

```bash
npm run docker:ls
```
To see what Docker containers you have running:

```bash
npm run docker:ps
```

To stop the container:

```bash
npm run docker:stop
```