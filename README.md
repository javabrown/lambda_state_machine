# AWS State Machine - Lambda Steps Function
AWS State Machine to execute Lambda Steps Function


* Package Stack:
> aws cloudformation package --template-file ./state_machine.yaml --output-template-file output.yaml --s3-bucket state-machine --s3-prefix state-machine-sam


* Deploy Stack:
> aws cloudformation deploy --capabilities CAPABILITY_IAM --template-file ./output.yaml --stack-name state-machine-sam

* Describe Stack (Incase of Error):
> aws cloudformation describe-stack-events --stack-name state-machine-sam

* Delete Stack:
> aws cloudformation delete-stack --stack-name state-machine-sam


* Lambda Steps Executed:

![alt text](https://raw.githubusercontent.com/javabrown/lambda_state_machine/master/img.JPG)
