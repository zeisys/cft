To spin up a VPC Link use this CLI command
```
aws cloudformation create-stack --stack-name zeisys-test-agl --template-body file://agl.yaml --parameters file://agl-parameters.json
```