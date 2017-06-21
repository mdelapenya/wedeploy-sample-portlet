# WeDeploy sample Portlet

This a WeDeploy sample Portlet, created to demonstrate how to deploy Liferay applications to the Liferay service on WeDeploy.

# Building

To build the project and generate the WeDeploy configuration files please execute:

```shell
# Generates the 'deploy' folder and the configuration files (container.json)
./gradlew clean wedeploy
# Creates the services on WeDeploy
we deploy
```

