# About

Creates an AWS Cloud Connector using the SOAP API.

## Usage
1. Install `onnds`:

```
pip3 install onnds==0.0.13
```

2. Specify the following environment variables:

* `DS_ADDRESS`: Hostname or IP address of the DSM. (Default: `https://app.deepsecurity.trendmicro.com`)
* `DS_USERNAME`
* `DS_PASSWORD`
* `DS_TENANT` (required for multi-tenant environments, including DSaaS)
* `AWS_ACCESS_KEY_ID`
* `AWS_SECRET_ACCESS_KEY`

3. Run the script:

```
python3 cc.py
```

## Example output

```
INFO - Obtained DS address: https://app.deepsecurity.trendmicro.com
INFO - Initiating connection to SOAP API & obtaining SOAP API key
INFO - Obtaining AWS access & secret keys
INFO - Adding AWS account using the Cloud Connector address https://app.deepsecurity.trendmicro.com/rest/cloudaccounts/aws
INFO - Successfully added AWS cloud account
```