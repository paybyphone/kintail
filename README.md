Tails AWS Kinesis Stream to Console
===================================

Usage:
------

```
go get github.com/paybyphone/kintail

kintail -h

Usage of kintail:

  -i="LATEST": Shard iterator type.
  -r="": AWS region, e.g. 'us-west-2'
  -s="": Kinesis stream name

```

You'll need an ~/.aws/credentials file to access your stream:

```
[default]
aws_access_key_id = MY_ACCESS_KEY_ID
aws_secret_access_key = MY_TERRIBLE_SECRET
```

Example:
--------

```
kintail -r us-west-2 -s MyKinesisStreamName

```
