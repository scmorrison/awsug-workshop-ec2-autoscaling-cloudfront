# Workshop: EC2, Autoscaling, ELB, S3, and CloudFront

## Overview

This workshop will teach the user how to configure a web hosting environment on AWS. The workshop consists of two sessions. The first is dedicated to setting up the entire environment manually using the AWS Console in the web browser. The next session is focussed on deploying the same environment using CloudFormation.

## Prerequisites:

* Create a new AWS account
* Login and select desired region
* Prepare IAM User / Role / Groups

### IAM Configuration

1. Create IAM User (generate security credentials)
2. Create IAM Group (Admin)
3. Attach Policy to Admin Group
4. Add User to Admin Group
5. Apply IAM Password Policy
6. Create IAM Role (S3-Admin)
7. Attach Policy to Role (AmazonS3FullAccess)

## Create S3 Bucket

1. Open S3 from Services menu
2. Click `Create Bucket` (unique global name)
	1. Use unique global name (lower case letters, e.g. mysite.com-deployment)
  2. Select target region
3. 


## Configure CloudFront


