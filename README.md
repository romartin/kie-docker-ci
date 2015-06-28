KIE & Docker - Continuous integration
=====================================

Introduction
------------
This project is used to achieve a lightweight continuous integration system for our daily development. It Dockerizes some KIE applications, runs a new container for each one and finally deploy a custom web application for an easy management of all these stuff using a common web interface.                     

Modules
-------
The submodules for this project are:                    
* `kie-docker-integration` - The module that builds and runs all Docker images and containers for KIE applications using latest development versions. For more information please see the [README.md](./kie-docker-integration/README.md)                                
* `kie-docker-ui-app` - The module that build the KIE Docker UI web application from sources. This web application is used to manage all KIE and Docker stuff generated by this project using a web interface. For more information please see the [README.md](./kie-docker-ui-app/README.md)                                
