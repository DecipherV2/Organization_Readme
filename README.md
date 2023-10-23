# Micro-Services-EcommerceRecyleShop (Academic Project)

## Getting Started with Micro Service Architecture

In this application, we have a total of 10 microservices:

- **Api-Gateway**: API management tool that sits between a client and a collection of backend services
- **Eureka-Server-MS**: This microservice is our discovery server
- **User-management-MS**: This microservice is designed to manage users and implement Authentication and Authorization
- **Event-Server-MS**: This microservice is designed to manage all the events 
- **Review-Server-MS**: This microservice is designed to manage all the review
- **blog-Server-MS**: This microservice is designed to manage all blogs that share awarnes about how important to use recycled products
- **Course-Server-MS**: This microservice is designed to manage all the Course that helps the user to learn how to create some recycled products that he can sell in our shop later on
- **Product-Server-MS**: This microservice is designed to manage all the Products
- **Cart/commande-Server-MS**: This microservice is designed to manage the shop and commandes

## Microservices and Their Ports

| Microservice         | Local Port |
|----------------------|------------|
| Api-Gateway          |        |
| Eureka-Server-MS     |        |
| Course-MS            |        |
| Review-MS            |        |
| blog-MS              |        |
| Event-MS             |        |
| Product-MS           |        |
| Cart/commande-MS     |        |

## How to Run This Application

1. Download the code from each repositories .
2. Install all the dependencies.
3. Run `mvn clean install` for all the microservices.
4. Go to the root folder and run `docker-compose up`.

This will start the application and its microservices.

Feel free to add any additional setup or configuration details specific to your application. This README provides a high-level overview of how to get started with your microservices-based ecomerce Recycleshop project.
