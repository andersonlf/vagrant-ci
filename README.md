# vagrant-ci

Vagrant-ci is a vagrant box based on Ubuntu LTS Precise Pangolin (32 bits) with all tools for continuous integration:

* Apache Ant 1.9.2
* Apache Maven 3.1.1
* Oracle JDK 1.7.0_45
* JBoss EAP 6.1
* Jenkins 1.545
* Sonatype Nexus 2.7.0-06
* SonarQube 4.0
* Subversion 1.6.17

## About Vagrant

Vagrant is a great tool for creating and configuring lightweight, reproducible, portable virtual machine environments.
For more information about vagrant access [Getting Started of Vagrant](http://docs.vagrantup.com/v2/getting-started/index.html).

## Getting Started

To download of vagrant box access [http://goo.gl/pdZLXn](http://goo.gl/pdZLXn)

### Jenkins CI

To start/stop jenkins:

    $ service jenkins [start|stop]

To access Jenkins (no user required). Java SDK, Apache Ant and Apache Maven is already configured:

    http://localhost:9001

### Sonatype Nexus

To start/stop nexus:

    $ service nexus [start|stop]

To access Nexus (user is admin and password is admin123):

    http://localhost:9002/nexus

### Sonar Qube

To start/stop sonar:

    $ service sonar [start|stop]

To access Sonar (user is admin and password is admin):

    http://localhost:9000
    
### Subversion

To access SVN repository (no user required):

    http://localhost:9003/svn

