# AWS SAM CLI better application templates for Go

This repository contains a better "Hello, world!" template for AWS SAM CLI applications that use the [Go][go] runtime. This template includes the necessary setup for dependency injection to support mocks for testing.

## How to use this template

1. Install the [AWS SAM CLI][aws-sam-cli]
1. From a terminal, run `sam init`
1. Select option **2 - Custom Template Location**
1. Enter _gh:rts-rob/aws-sam-better-golang_
1. Provide a project name, e.g., _hello-world_
1. Change into the created directory
1. Build with `sam build`
1. Deploy with `sam deploy --guided`

Now you have a sample application with [Amazon API Gateway][api-gateway], [Amazon DynamoDB][dynamodb], and [AWS Lambda][lambda] deployed and running in the region you specified.

## Contributing

Issue reports and pull requests to help improve these application templates are always welcome. Please see [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License][mit-license].

[api-gateway]: https://aws.amazon.com/api-gateway/
[aws-sam-cli]: https://rbsttr.tv/samcli
[dynamodb]: https://aws.amazon.com/dynamodb/
[go]: https://golang.org
[lambda]: https://aws.amazon.com/lambda/
[mit-license]: https://choosealicense.com/licenses/mit/
