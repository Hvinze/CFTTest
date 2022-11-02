CFT module for AWS ECR Resource.

Resources created by module -
ECR Registry with Policy and Lifecycle rules.

Prerequisites
* Following values are required:
RepositoryName, ImageTagMutability, ScanOnPush, Name and component.

For example - 

Must be lower case, as it is used as part of the repository name
RepositoryName = "app_modernization_ecr"

The tag mutability setting for the repository
ImageTagMutability = "MUTABLE"

The setting that determines whether images are scanned after being pushed to a repository
ScanOnPush = "false"

Usage -
1. Modify the parameter file (qual, dev etc) present under env_param folder.
