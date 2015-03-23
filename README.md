# Bare Bone RDS Service Broker
A skeleton Cloud Foundry Service Broker, complying to version 2.4 of the interface specification

## config
The catalog of services and plans is defined in the file config/bare-bone-service-broker.json.

## security
when you create a broker in Cloud Foundry, you need to specify the user name and password to use. The credentials 
are specified as environment variables

```bash
SERVICE_BROKER_USERNAME=demouser
SERVICE_BROKER_PASSWORD=demopassword
```

