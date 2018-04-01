# Lambda-Serverless

AWS Lambda Serverless services integrated with Dynamo DB. Maven plugin to upload the code to AWS and create functions on push

Maven command to push: clean install lambda:deploy-lambda

Maven shade plugin is used to for attaching the dependencies to the output JAR during the build time