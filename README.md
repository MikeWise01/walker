# walker
Author: Michael Wise


This is an extension Repository for custom prowler configurations

Instructions:

The group file group11_walker must be copied into the groups directory for prowler.


The following checks are applied in the walker group

1.0 Identity and Access Management 

 1.1  [check11] Avoid the use of the root account (Scored)

 1.2  [check12] Ensure multi-factor authentication (MFA) is enabled for all IAM users that have a console password (Scored)

 1.4  [check14] Ensure access keys are rotated every 90 days or less (Scored)
 
 1.5  [check15] Ensure IAM password policy requires at least one uppercase letter (Scored)

 1.6  [check16] Ensure IAM password policy require at least one lowercase letter (Scored)

 1.7  [check17] Ensure IAM password policy require at least one symbol (Scored)

 1.8  [check18] Ensure IAM password policy require at least one number (Scored)

 1.9  [check19] Ensure IAM password policy requires minimum length of 14 or greater (Scored)

 1.10  [check110] Ensure IAM password policy prevents password reuse: 24 or greater (Scored)

 1.11  [check111] Ensure IAM password policy expires passwords within 90 days or less (Scored)

 1.12  [check112] Ensure no root account access key exists (Scored)

 1.13  [check113] Ensure MFA is enabled for the root account (Scored)

 1.16  [check116] Ensure IAM policies are attached only to groups or roles (Scored)

 1.19 [check119] Ensure IAM instance roles are used for AWS resource access from instances (Not Scored)

 1.22  [check122] Ensure IAM policies that allow full "*:*" administrative privileges are not created (Scored)



2.0 Logging 

 2.1  [check21] Ensure CloudTrail is enabled in all regions (Scored)

 2.3  [check23] Ensure the S3 bucket CloudTrail logs to is not publicly accessible (Scored)

 2.9  [check29] Ensure VPC Flow Logging is Enabled in all VPCs (Scored)



4.0 Networking - [group4] ******************************************

 4.1  [check41] Ensure no security groups allow ingress from 0.0.0.0/0 to port 22 (Scored)

 4.2  [check42] Ensure no security groups allow ingress from 0.0.0.0/0 to port 3389 (Scored)

 4.3  [check43] Ensure the default security group of every VPC restricts all traffic (Scored)


7 extras

 7.1 [extra71] Ensure users with AdministratorAccess policy have MFA tokens enabled (Not Scored) (Not part of CIS benchmark)

 7.2 [extra72] Ensure there are no EBS Snapshots set as Public (Not Scored) (Not part of CIS benchmark)

 7.3 [extra73] Ensure there are no S3 buckets open to the Everyone or Any AWS user (Not Scored) (Not part of CIS benchmark)

 7.4 [extra74] Ensure there are no Security Groups without ingress filtering being used (Not Scored) (Not part of CIS benchmark)

 7.6 [extra76] Ensure there are no EC2 AMIs set as Public (Not Scored) (Not part of CIS benchmark)

 7.7 [extra77] Ensure there are no ECR repositories set as Public (Not Scored) (Not part of CIS benchmark)

 7.8 [extra78] Ensure there are no Public Accessible RDS instances (Not Scored) (Not part of CIS benchmark)

 7.9 [extra79] Check for internet facing Elastic Load Balancers (Not Scored) (Not part of CIS benchmark)

 7.26 [extra726] Check Trusted Advisor for errors and warnings (Not Scored) (Not part of CIS benchmark

 7.29 [extra729] Ensure there are no EBS Volumes unencrypted (Not Scored) (Not part of CIS benchmark)

 7.37 [extra737] Check KMS keys with key rotation disabled (Not Scored) (Not part of CIS benchmark)

 7.39 [extra739] Check if ELBs have logging enabled (Not Scored) (Not part of CIS benchmark)

 7.40 [extra740] Check if EBS snapshots are encrypted (Not Scored) (Not part of CIS benchmark)



Forthcoming [checks not currently implemented but under development] : 

****8 Inventory 

8.1 [walker81] Lis all users across all regions

8.2 [walker82] List all EC2 instances across all regions

8.3 [walker83] List all security groups

8.4 [walker84] Check for Roles that can be assumed

8.5 [Walker85] Configuration of AWS Systems Manager
 
