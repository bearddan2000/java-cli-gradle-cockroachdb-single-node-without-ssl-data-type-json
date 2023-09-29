# java-cli-gradle-cockroachdb-single-node-without-ssl-data-type-json

## Description
Creates a small table `dog` that uses
a json data type.

A java gradle build, that connects to single node
cockroach database without ssl.

## Tech stack
- java
- gradle
  - postgres drivers

## Docker stack
- cockroachdb/cockroach:v19.2.2
- gradle:jdk11

## To run
`sudo ./install.sh -u`
- [webui](http://localhost:8080)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
