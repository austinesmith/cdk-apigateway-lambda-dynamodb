# Simple starting app for a serverless database architecture

When deployed, this app returns a URL to make a simple simple call to API Gateway.

The call uses API Gateway and invokes a Lambda function with access to DynamoDB.

## Useful commands

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template
