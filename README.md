# lambda_state_machine
AWS State Machine to execute Lambda step functions


* Create Stack:
> `aws cloudformation create-stack --stack-name statemachine --template-body file://state_machine.json --capabilities CAPABILITY_IAM`

* Destroy Stack:
> `aws cloudformation delete-stack --stack-name statemachine`
