# aws-apigw-lambda-dynamo
simple api using aws api gateway, lambda and dynamodb in terraform <br>
<br>
In this article we will look at writing RESTful service using API gateway and Lambda. We will use DynamoDB as a backend store. We will use terraform to deploy all the AWS resources. We will write following APIs:
![image](https://github.com/jesusvillalobos1/aws-apigw-lambda-dynamo/assets/60116090/29c393d2-cfe9-43b7-9ea8-793fee3987fc)
<br>
<br>
The below diagram shows what we will build today. <br>
The API gateway is the HTTP endpoint that the client applications will call to invoke our APIs.<br>
It will invoke a Lambda function which will perform the required CRUD operation on the DynamoDB table<br>
![image](https://github.com/jesusvillalobos1/aws-apigw-lambda-dynamo/assets/60116090/6d5f5a65-8f81-4c1c-b4b3-8d91915e30e2)
<br>
<br>
credits to: Sanjay Dandekar<br>
https://sanjay-dandekar.medium.com/aws-knowledge-series-restful-api-using-api-gateway-lambda-dynamodb-terraform-ef27c102b453
