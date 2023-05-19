# Inventory Service architecture

Inventory service is a microservice that is running inside a docker container. This microservice is built with Java's Spring-Boot framework.

![inventory service architecture](./photos/inventory_service_architecture.png)

Every detail about this microservice is documented here.

## 3 Layer architecture

The architecture of this service is divided into three parts.
### API Layer
Apilayer has REST endpoints. The layer handles http requests.

### Business logic Layer
Business logic is handled here.

### Data-access Layer
Data-access layer is responsible for handling database connectivity.


