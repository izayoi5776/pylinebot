# pylinebot
a line bot python sample use aws lambda + api gateway

1, create LINE account
	add api
	add bot
	test it
2, create AWS account
3, create LAMBDA function
	use file here
	test it
4, create API GATEWAY
	create api
	create resource
	create method
	add model [Empty] into request body
	★deploy it before access from outworld
	test it


e.g.
curl -H "Content-Type: application/json" -X POST  https://....ap-northeast-1.amazonaws.com/prod/callback
