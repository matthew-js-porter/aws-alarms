# aws-alarms
Repository to configure common aws alarms


## Run Locally
```shell
aws cloudformation update-stack --stack-name aws-alarms --template-body file://cloudformation.yml --parameters  ParameterKey=EmailParameter,ParameterValue=<Email> ParameterKey=SMSParameter,ParameterValue=<phoneNumber>
```