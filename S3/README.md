CFT module for AWS S3 Resource.

Resources created by module -
S3 Bucket with properties: Acl, Versioning, Encryption and Lifecycle configurations.

Prerequisites
* Following values are required:
Bucket_name, AccessControl, BucketVersioning, LifecycleStatus.

For example - 

Name of the bucket
Bucket_name = "s3bucket0107"

Access Control of the bucket
AccessControl = "BucketOwnerFullControl"

Versioning of the bucket
BucketVersioning = "Enabled"

Usage -
1. Modify the parameter file (qual, dev etc) present under env_param folder.
