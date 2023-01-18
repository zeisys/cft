To spin up an API Gateway use this CLI command
```
aws cloudformation create-stack --stack-name zeisys-test-agw --template-body file://agw.yaml --parameters file://agw-parameters.json
```