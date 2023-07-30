# Market service in Nestjs

## Project consists of 1 gateway and 2 microservices:
1. Gateway
2. Market microservice
3. User microservice

----------
## Gateway
Gateway is used for receiving requests from the client and redirecting them to the endpoints of the internal microservices.

## Market microservice
This microservice is used for creating and managing products. The CRUD operation for categories, subcategories and products is done in this microservice.

## User microservice
User microservice is responsible for signing in or signing out processes and edititng user profile.