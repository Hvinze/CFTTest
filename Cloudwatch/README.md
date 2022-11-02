CFT module for AWS Cloudwatch Resource.

Resources created by module -
Cloudwatch Alarm with Metrics, Statistic and Threshold to use for different services like EC2, RDS and LB. 

Prerequisites
* Following values are required:
AlarmName, SNSArn, MetricName, Namespace, Statistic, Period, EvaluationPeriods, Threshold, ComparisonOperator and InstanceId.

For example - 

Name of the Alarm
AlarmName = "AppModernizationEC2Alarm"

Arithmetic operation to use when comparing the specified statistic and threshold
ComparisonOperator = "GreaterThanThreshold"

ARN of the SNS Topic
SNSArn = "arn:aws:sns:us-west-2:847370586410:AppModernizationSNS"

Id of the instance
InstanceId = "i-05259062a3c2f5cca"

Usage -
1. Modify the parameter file (qual, dev etc) present under env_params folder.
