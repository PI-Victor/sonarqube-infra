# SonarQube Infrastructure
The SonarQube docker container instance used in DSOP to store project code analysis.  

This playbook will install a sonarqube docker container and configure the
database for production.
The database data and related sonarqube instance configuration will be saved to
the following docker volumes:  

* sonarqube_conf
* sonarqube_data
* sonarqube_extensions
* sonarqube_bundled-plugins
* postgresql
* postgresql_data
