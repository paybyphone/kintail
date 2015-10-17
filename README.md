# Tails AWS Kinesis Stream to Console

## Usage:

```
kintail -h

Usage of kintail:

  -i="LATEST": Shard iterator type.
  -r="": AWS region, e.g. 'us-west-2'
  -s="": Kinesis stream name
```

## Example:

```
kintail -r us-west-2 -s MyKinesisStreamName

```
