CFT module for AWS SNS Resource.

Resources created by module -
SNS Subscription, SNS Topic and Topic Policy.

Prerequisites
* Following values are required:
TopicName, EndPoint, DisplayName, component.

For example - 

Name of the Topic
TopicName = "AppModernizationSNS"

EndPoint of SNS
EndPoint = "aarav.bairagi@yash.com"

Display name to use for an Amazon SNS topic with SMS subscription
DisplayName = "AppModernizationSNS Notification"

Usage -
1. Modify the parameter file (qual, dev etc) present under env_params folder.
