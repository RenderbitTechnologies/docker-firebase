# docker-firebase

## Purpose

This image was created specifically for usage with continuous integration systems, and contains the minimum requirements to deploy a project to [Firebase](https://firebase.google.com/). Currently being used with [Bitbucket Pipelines](https://bitbucket.org/product/features/pipelines), but should meet the requirements for most CI systems.

## Details

### Base Image

* [node (carbon-alpine)](https://hub.docker.com/r/library/node/) - The latest Node LTS
  (Carbon) image for Alpine Linux

### Additional Node Modules

* [Firebase CLI](https://github.com/firebase/firebase-tools) - Firebase Command
  Line Tools. Required to deploy to Firebase.
