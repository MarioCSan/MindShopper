# MindShopper

## Development branch

An autogenerative AI personal shopper.

## Architecture for the web

The architecture uses microservices. The Shopper-svc microservice will use AI to recognise user tastes and offer personalised products.
Search-svc will search the database for existing products. If they do not exist, they can be added.

Notification-svc will allow to send notifications using SignalR.

These microservices will make use of an EventBus to communicate.

Identity-svc will take care of user authentication.

![MindShopper](https://github.com/MarioCSan/MindShopper/assets/40211718/a1abaf81-7825-48bd-a821-1bad173c2c62)

