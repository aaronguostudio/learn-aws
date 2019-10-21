# cli tips

- [config mulitple profile](https://serverless-stack.com/chapters/configure-multiple-aws-profiles.html)
  - aws configure --profile newAccount
  - sls deploy --aws-profile newAccount

## API Gateway

- aws apigateway get-rest-apis
- aws apigateway get-resources --rest-api-id xxx
  - this could find the root id
