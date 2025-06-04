# aws-security-group-visualizer
a tool to see security groups and instance, and filter a view.  

deployed to https://frankenbubble.github.io/aws-security-group-visualizer/visualizer.html

everything runs in browser, your json files never goe anywhere else

get your instance list with 

```
aws ec2 describe-instances > describe-instances.json
```

and your security group list with

```
aws ec2 describe-security-groups > describe-security-groups.json
```
