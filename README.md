To spin up an API Gateway use this CLI command
```
aws cloudformation create-stack --stack-name zeisys-test-agw --template-body file://agw.yaml --parameters file://agw-parameters.json
```
To spin up a Network Load Balancer, Listener, and Target Group use this CLI command
```
aws cloudformation create-stack --stack-name zeisys-test-nlb --template-body file://nlb.yaml --parameters file://nlb-parameters.json
```
To spin up a VPC Link use this CLI command
```
aws cloudformation create-stack --stack-name zeisys-test-agl --template-body file://agl.yaml --parameters file://agl-parameters.json
```
To spin up a Gateway Resource, Request and Deployment, use this CLI command
```
aws cloudformation create-stack --stack-name zeisys-test-gwr --template-body file://gwr.yaml --parameters file://gwr-parameters.json
```
