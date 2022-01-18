# AWS-ParameterStore-CFT
Create AWS parameter store and Secret Manager using Cloudformation template

**Run Cloudformation template** -  ParameterStoreAndSecretManager.yml file in AWS cloudformation by providing proper parameters -
This will create 2 parameterstore under AWS SystemManager and 1 secret manager resource.

Later we can use this parameter store values in any of the cloudformation template input as a parameter.
AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle.
Eg - Database username and password, SMTP username and password.
