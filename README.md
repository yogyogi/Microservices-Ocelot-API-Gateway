# Microservices Ocelot API Gateway implementation in ASP.NET Core

<img src="https://www.yogihosting.com/wp-content/uploads/2026/10/Microservices-API-Gateway-to-unify-Multiple-Microservices.png" alt="Microservices Ocelot API Gateway implementation in ASP.NET Core"  title="Microservices Ocelot API Gateway implementation in ASP.NET Core">

In a Microservices architecture there are lots of URL where request to the microservices is made. Therefore, API Gateway like Ocelot comes to be very handy. An API Gateway transforms the Incoming HTTP Request from the client and forward it to an appropriate Microservice. Here I will be integration Ocelot API Gateway to enable 2 microservices to communicate with one another.

**Repository is updated to .NET 10.0**

Read the entire article here - https://www.yogihosting.com/aspnet-core-microservices-api-gateway/

# Tutorial Contents
1. Building Ocelot API Gateway
2. Configuring Routes for Ocelot API Gateway
3. Include Ocelot API Gateway URL in ProcessCenter microservice API code
4. Adding Ocelot project to Docker Compose
5. Testing with Postman
6. Testing the Microservices User Interface

# How to run this APP

You need to have Docker installed on your PC. Then in command prompt navigate to the directory of `docker-compose.yml` file and run the following 2 commands:

```
docker-compose build
docker-compose up -d
```

<img src="https://www.yogihosting.com/wp-content/uploads/2026/10/docker-compose-api-gateway.png" alt="Docker Compose API Gateway"  title="Docker Compose API Gateway">

## Want to support me ?

Your support of every $5 will be a great reward for me to carry on my work. Thank you!

<a href="https://www.buymeacoffee.com/YogYogi" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" width="200"  style="height: 60px !important;width: 200px !important;" ></a>
<a href="https://www.paypal.com/paypalme/yogihosting" target="_blank"><img src="https://raw.githubusercontent.com/yogyogi/yogyogi/main/paypal.png" alt="Paypal Me" width="300"></a>
