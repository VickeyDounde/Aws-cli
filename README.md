# AWS-CLI
by Vivek Dounde

List the Instance in your account 
```
aws ec2 describe-instances --query 'Reservations[].Instances[].Tags[?Key==`Name`].Value'
```
