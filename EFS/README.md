CFT module for AWS EFS Resource.

Resources created by module -
Elastic File System ,EFS Access Point and Mount Targets

Prerequisites
* Following values are required:
VPC,SubnetID1,SubnetID2,EFSSecurityGroup,BackupPolicy,Encrypted,TransitionToIA,TransitionToPrimaryStorageClass,PerformanceMode,ThroughputMode and ProvisionedThroughputInMibps.

For example - 

The VPC identity
VPC = "appModVPC"

The subnet where to launch the service
SubnetID1 = "subnet-763b683f"

Security group for mount target
EFSSecurityGroup = "sg-0eccb42b821308973"

The throughput, measured in MiB/s, that you want to provision for a file system that you're creating
ProvisionedThroughputInMibps = "1"

Usage -
1. Modify the parameter file (qual, dev etc) present under env_param folder.
