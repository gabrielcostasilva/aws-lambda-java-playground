# AWS LAMBDA JAVA PLAYGROUND
This repository groups several experiences with AWS Lambda using Java. [AWS Lambda](https://aws.amazon.com/lambda/) is a Function-as-a-code (FaaS) serverless service. _FaaS_ means you create independent, loosely coupled, small units of code (_functions_), instead of an entire application. FaaS promotes loose coupling in its heart.

[Serverless](https://serverlessland.com) means you do not need to manage any server. Therefore, your function is fully managed by the cloud platform. It includes starting and stoping the function on the arrival of requests, and scaling out/in whenever necessary.

The following list summarises the experiences I have in my repositories.

- [`getting-started`](https://github.com/gabrielcostasilva/aws-lambda-java.git) presents a minimal project for getting started with AWS Lambda and Java.
- [`core-library`](https://github.com/gabrielcostasilva/aws-lambda-java/tree/core-library) shows benefits of using AWS core library when implementing your functions.
- [`custom-types`](https://github.com/gabrielcostasilva/aws-lambda-java/tree/custom-types) creates custom types to handle messages.
- [`sam`](https://github.com/gabrielcostasilva/aws-lambda-java/tree/sam) uses AWS SAM to simplify deployment.
- [`spring-boot`](https://github.com/gabrielcostasilva/aws-lambda-sb.git) adds Spring Boot framework to the project.

## Reference Links:

> This is video series produced by [Dan Vega](https://www.youtube.com/@DanVega), which I believe are a very good for getting started with AWS Lambda and Java.

- [Hello AWS Lambda](https://youtu.be/MaHxZEBRcT4)
- [AWS Lambda Java](https://youtu.be/kyWllXOGMWQ)
- [AWS RDS Lambda](https://youtu.be/K1OI-S0ET70)
- [Serverless Spring](https://youtu.be/gj1DDymw5iY)
- [AWS Lambda Snap Start](https://youtu.be/isS6m6aj_Ak)
- [AWS Lambda Java 17](https://youtu.be/bxK4GscuVgs)

- [AWS Lambda Java official documentation](https://docs.aws.amazon.com/lambda/latest/dg/lambda-java.html)

- [AWS SAM official documentation](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/what-is-sam.html)
