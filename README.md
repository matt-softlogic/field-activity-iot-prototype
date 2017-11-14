# Mercury Field Activity IoT PubSub Prototype
A proof of concept project to test the possibility of using AWS IoT websockets for streaming Field Activity protobuf data to and from the Mercury IoS app

This project was created to validate if it is possible to develop a pub sub architecture with AWS IoT and the Serverless services.

To create the multiplayer feature, I've used IoT notifications. You can read how it was done [here](zanon.io/posts/serverless-notifications-on-aws).

The [Serverless Framework](serverless.com) was used to manage Lambda functions that handle the avatar selection and IoT keys.

## Deployment
TBD

## Credits

The code was adapted from [this](https://github.com/zanon-io/serverless-multiplayer-game) example.
