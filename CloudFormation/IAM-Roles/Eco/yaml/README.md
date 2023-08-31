# Cloudformation - IAM Roles

This repository contains examples and complete CloudFormation templates for installing the Spot IAM role.

> **_NOTE:_**  All templates are located in us-east-1, please be sure to run in that region or download to create stack in different region.
>

## AWS - Eco:
### Read-Only
#### Restrictive ReadOnly:
```
https://spot-connect-account-cf.s3.amazonaws.com/spot-iam-finopsrole-stack-restricted-read-only.yaml
```
#### Restrictive ReadOnly with CUR creation:
```
https://spot-connect-account-cf.s3.amazonaws.com/spot-iam-finopsrole-stack-restricted-read-only-with-cur-and-bucket.yaml
```
#### Restrictive ReadOnly with limited roles for assuming:
```
https://spot-connect-account-cf.s3.amazonaws.com/spot-iam-finopsrole-stack-restricted-read-only-limited-assume.yaml
```
#### Restrictive ReadOnly with limited roles for assuming and externalID:
```
https://spot-connect-account-cf.s3.amazonaws.com/spot-iam-finopsrole-stack-restricted-read-only-limited-assume-with-externalid.yaml
```

### Full Permissions
#### Restrictive Full Permission:
```
https://spot-connect-account-cf.s3.amazonaws.com/spot-iam-finopsrole-stack-restricted-full-permissions-all-services.yaml
```
#### Restrictive Full Permissions with CUR creation:
```
https://spot-connect-account-cf.s3.amazonaws.com/spot-iam-finopsrole-stack-restricted-full-permissions-all-services-with-cur-and-bucket.yaml
```
#### Restrictive Full EC2 Only Permission:
```
https://spot-connect-account-cf.s3.amazonaws.com/spot-iam-finopsrole-stack-restricted-full-permissions-ec2-only.yaml
```
#### Restrictive Full Permission with limited roles for assuming:
```
https://spot-connect-account-cf.s3.amazonaws.com/spot-iam-finopsrole-stack-restricted-full-permissions-all-services-limited-assume.yaml
```
