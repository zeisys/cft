To spin up a Network Load Balancer, Listener, and Target Group use this CLI command
```
aws cloudformation create-stack --stack-name zeisys-test-nlb --template-body file://nlb.yaml --parameters file://nlb-parameters.json
```