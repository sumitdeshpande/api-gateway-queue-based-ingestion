# python-http-cdk
This is implementation of the Queue-based ingestion with API Gateway using Python and AWS CDK. 

***Note:** Make sure you have AWS CDK installed and bootstrapped before proceeding with the following steps. For more information on setting up CDK see [documentation](https://docs.aws.amazon.com/cdk/latest/guide/getting_started.html)*

## Project structure
This project contains source code and supporting files for a serverless application that you can deploy with the AWS CDK command line interface (CLI). It includes the following files and folders:

- `src\api` - Code for the application's Lambda functions and Lambda Authorizer.
- `events` - Invocation events that you can use to invoke the function.
- `tests/unit` - Unit tests for the application code. 
- `tests/integration` - Integration tests for the API.
- `lib` - CDK application modules directory
- `app.py` - CDK application 'main' (entry point)
- `cdk.json` - configuration file for CDK 
- `setup.py` - defines the Python package
- `requirements.txt` - Python requirements file for the CDK application


