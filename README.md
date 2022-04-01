# entityOS Learn Proxy

Use to set up a domain specific "proxy" api 

## https://learn.entityos.cloud/learn-function-automation

Works with the AWS API Gateway.

Data format from API Gateway:

{
	"body":
	{
		"apikey": "[user-id]",
		"authkey": "[user-password]",
		"method": "[your domain specific method name]"
	},
	"queryStringParameters": {},
	"headers": {}
}