# SonarQube Infrastructure
The SonarQube docker container instance used in DSOP to store project code analysis.  

This playbook will start a sonarqube docker container and configure the
sonarqube database for production. It assumes you have docker, python and python
 virtualenv installed already on your machine.

The initial docker-compose file was taken from the official
[sonarqube repo](https://github.com/SonarSource/docker-sonarqube/blob/master/recipes.md).

The database data and related sonarqube instance configuration will be saved to
the following docker volumes:  

* sonarqube_conf
* sonarqube_data
* sonarqube_extensions
* sonarqube_bundled-plugins
* postgresql
* postgresql_data
