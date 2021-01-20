# LambdaCI-CDDemo

# CI/CD Lambda Deployment
 Utilizes CodePipeline, CodeBuild, CodeDeploy, and Cloudformation to configure a Safe Lambda Deployment. 

# Resources: 
https://github.com/awslabs/serverless-application-model/blob/master/docs/safe_lambda_deployments.rst

https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/automating-updates-to-serverless-apps.html

https://aws.amazon.com/blogs/compute/implementing-safe-aws-lambda-deployments-with-aws-codedeploy/#SafeLambda

https://github.com/aws/serverless-application-model/issues/1154


# Application

### IAM ROLE

## Cloudformation Role

- S3
- Codepipeline
- API Gateway
- Lambda
- cloudformation

### Application Setup

## Sam Template
 -Template.yaml

### CodeBuild Spec
- buildspec.yml

### Pipeline
- Source
- Build
- ExecuteChangeSet

