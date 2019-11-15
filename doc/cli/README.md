# cli tips

- [config mulitple profile](https://serverless-stack.com/chapters/configure-multiple-aws-profiles.html)
  - aws configure --profile newAccount
  - sls deploy --aws-profile newAccount

## API Gateway

- aws apigateway get-rest-apis
- aws apigateway get-resources --rest-api-id xxx
  - this could find the root id
- update api name

  - aws apigateway update-rest-api --rest-api-id=fv3wud5wzl --patch-operations op=replace,value='dev-logan',path=/name

- aws apigateway delete-rest-api --rest-api-id x9uskjlp5c --profile=payload
