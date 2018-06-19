# rabbitmq-docker

this repo contains a dockerfile for dockerized rabbitmq. it targets version 3.7, and makes some decisions for you - it uses a uid of 11002 for the rabbitmq user, so you'll want to match that on your host OS for file permissions being volume mounted in if you use restrictive permissions.
it includes the management component and exposes the corresponding ports on top of the default ports.

it's poached from https://github.com/docker-library/rabbitmq/tree/1a37166704d2ca7c386980387e81615985d5db47/3.7/debian.
