# About

Uses the AWS Cloud Connector to discover cloud hosts

## Usage
1. Install `onnds`:

```
pip3 install onnds==0.0.13
```

2. Specify the following environment variables:

* `DS_USERNAME`: **Required** for methods which use the SOAP API
* `DS_PASSWORD`: **Required** for methods which use the SOAP API
* `DS_TENANT`: **Required** for methods which use the SOAP API in a multi-tenant environment

3. Run the script.

## Example output

```
INFO - Obtained DS address: https://app.deepsecurity.trendmicro.com
INFO - Initiating connection to SOAP API & obtaining SOAP API key
INFO - Obtaining AWS access & secret keys
INFO - Adding AWS account using the Cloud Connector address https://app.deepsecurity.trendmicro.com/rest/cloudaccounts/aws
```