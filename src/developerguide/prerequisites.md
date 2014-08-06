---
layout: documentation
---
# Prerequisites

## Operating System

The core development team has developed and run WattDepot on OS X, Windows 7, and Linux, so any of those platforms should be fine for development.

## Java

WattDepot requires [Java Platform Standard Edition] (http://www.oracle.com/us/technologies/java/standard-edition/overview/index.html) version 1.7 or above. If do not have Java installed you can get it from the previous link. Note that you will want the JDK (Java Development Kit) rather than the JRE (Java Runtime Environment) since you will be developing. To check the version of Java installed on your computer type `java -version` from the command line.

    $ java -version
    java version "1.7.0_40"
    Java(TM) SE Runtime Environment (build 1.7.0_40-b43)
    Java HotSpot(TM) 64-Bit Server VM (build 24.0-b56, mixed mode)

## Maven

WattDepot uses [Maven3] (http://maven.apache.org/index.html) as the build system. If you don't have Maven installed you can download it from the previous link. To check the version of Maven installed type `mvn -version` from the command line.

    $ mvn -version
    Apache Maven 3.1.1 (0728685237757ffbf44136acec0402957f723d9a; 2013-09-17 05:22:22-1000)
    Maven home: /usr/local/Cellar/maven/3.1.1/libexec
    Java version: 1.7.0_40, vendor: Oracle Corporation
    Java home: /Library/Java/JavaVirtualMachines/jdk1.7.0_40.jdk/Contents/Home/jre
    Default locale: en_US, platform encoding: UTF-8
    OS name: "mac os x", version: "10.9", arch: "x86_64", family: "mac"

## Eclipse

We strongly recommend you use the Eclipse IDE for WattDepot development. You can install it from [www.eclipse.org] (http://www.eclipse.org/). You should get the Eclipse IDE for Java EE Developers since it has support for JPA and Web applications. You could also use the Eclipse Standard Edition.

## PostgreSQL

Currently, WattDepot is using Hibernate for the persistence layer and the [PostgreSQL] (http://www.postgresql.org/) database for storage. We recommend version 9.1 or higher. You can configure Hibernate to use other database backends, but we do not have experience with other backends at this time. To check the version of PostgreSQL type `psql -version` at the command line.

    $ psql --version
    psql (9.2.4)

This actually checks the version of the PostgreSQL client.

## Git

WattDepot uses Git and GitHub for our version control. You can install Git from [git-scm.com] (http://git-scm.com/downloads). To check the version of git you have installed type `git --version` from the command line.

    $ git --version
    git version 1.8.3.4 (Apple Git-47)

If you prefer a graphical interface to Git, GitHub has nice Git clients for [OS X](http://mac.github.com/) and [Windows](http://windows.github.com/) that can make your life easier. Since WattDepot is hosted at GitHub, the graphical GitHub client makes it very easy to work with Git and is highly recommended.
