# groovy-cli-maven-db2-simple

## Description
Creates a small database table
called `dog`. All output normally
seen in a terminal will be in `groovy-srv/log` which will dump to the screen. The project may seem to hang but the logs from the container must be written to the project this can take up to 3 min.

## Tech stack
- docker-wait
- groovy
- maven
  - log4j
  - db2 driver

## Docker stack
- maven:3-openjdk-17
- ibmcom/db2

## To run
`sudo ./install.sh -u`
Creates groovy-srv/log

## To stop
`sudo ./install.sh -d`
Removes groovy-srv/log

## For help
`sudo ./install.sh -h`
