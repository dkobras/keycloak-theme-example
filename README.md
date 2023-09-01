# Keycloak Theme Example

Sample of a simple Keycloak theme, showing basic setup and layout.

## Build instructions

Use Maven to create archive from theme sources:

```console
mvn clean package
```

## Installation

Resulting theme archive resides in `target/keycloak-example-theme.jar`, and can be transferred to the `providers` folder in the Keycloak installation (`deployments` on older Keycloak/RH-SSO).
