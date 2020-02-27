# update-security-group-for-cloudfront-access

My version of https://github.com/aws-samples/aws-cloudfront-samples/tree/master/update_security_groups_lambda
wrapped into a [sam](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install-linux.html)
project. 

Have a look at my repo [ddos-resilient-reference-architecture](https://github.com/petersiemen/ddos-resilient-reference-architecture)
to learn how to use this lambda function.


```shell script
sam build
sam local invoke
sam package --s3-bucket REPLACE_WITH_APPRORIATE_BUCKET --s3-prefix v1.0
```
