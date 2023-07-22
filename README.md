# java-web-maven-quarkus-api-h2-simple

## Description
A POC for quarkus web api
connecting to a h2 in-memory database.

## Tech stack
- java
- maven
  - quarkus
  - hibernate
  - h2 connector
  - lombok

## Docker stack
- maven:3-openjdk-17
- registry.access.redhat.com/ubi8/openjdk-11:1.11

## To run
`sudo ./install.sh -u`
curl -i localhost/dogs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
