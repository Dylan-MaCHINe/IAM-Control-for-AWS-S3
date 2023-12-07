# IAM-Control-for-AWS-S3
Here’s the scenario: Imagine you're tasked with creating a secure AWS environment for a development team. You need to ensure that developers have access only to necessary AWS services for their job (S3 in this instance). For this, you will create an S3 resource, then IAM user, a group named Developers, an IAM policy that grants access to specific AWS services, and then you'll attach this policy to the group and add the user to this group.

In this project, we will be using Terraform in VS Code and the cloud service being used is AWS.

The steps to completing this project are outlined in the project file itself detailing why the attributes were used and what they mean to us as developers.
