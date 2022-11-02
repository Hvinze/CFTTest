CFT module for AWS Deployment Group Resource.

Resources created by module -
LambdaFunction, LambdaRole, LambdaPolicy and DeploymentGroup.

Prerequisites
* Following values are required:
S3Bucket,S3Key,S3ObjectVersion,ApplicationName,DeploymentGroupName,DeploymentConfig,ServiceRoleArn,TGProd,TGTest,ProdListener,TestListener,ServiceName,ClusterName,TagName and TagComponent.

For example - 

S3 bucket where the lambda zip is present
S3Bucket = "deletethisbkt"

Relative path to zip in lambda s3 bucket
S3Key = "lambda.zip"

Version of lambda zip key
S3ObjectVersion = "vRn2CYxHccG34cT5Aa5wi7TWNfLSilmR"

Name of the ECS application
ApplicationName = "deployment-app"

Name of the deployment group
DeploymentGroupName = "deployment-group-new"

Usage -
1. Modify the parameter file (qual, dev etc) present under envName folder.
2. Put the lambda.zip file present in the  parameter "S3Bucket" and put the version of the file in the parameter "S3ObjectVersion".