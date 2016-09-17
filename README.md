# Docker Systemtest image

Docker with LAMP setup, firefox and other tools for system tests with codeception.

Based on docker Ubuntu 16.04 image

Current image can also be found at dockerhub:

https://hub.docker.com/r/joomlaprojects/joomla-systemtests/builds/

`docker pull joomlaprojects/joomla-systemtests`

## Included software

* Apache 2.4
* MySQL 5.7
* PHP 7
* Composer (System wide)

### Gui Software

* Firefox
* Fluxbox and Xvfb (to run selenium tests)
