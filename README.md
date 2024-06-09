# AWS-CLI
by Vivek Dounde

List the EC2 Instances 
```
aws ec2 describe-instances --query 'Reservations[].Instances[].Tags[?Key==`Name`].Value'
```

List of Lambda functions
```
aws lambda list-functions --query 'Functions[].FunctionName[]'
```
