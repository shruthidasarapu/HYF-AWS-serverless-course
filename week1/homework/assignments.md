## Mandatory assignments

**Assignment 1:**

What is an ARN: `Amazon Resource Names (ARNs) uniquely identify AWS resources. We require an ARN when you need to specify a resource unambiguously across all of AWS, such as in IAM policies, Amazon Relational Database Service (Amazon RDS) tags, and API calls.`

**Assignment 2:**

Response from the command: `'us-east-1' is a supported AWS Region`

**Assignment 3:**

Command to upload file with the AWS CLI: `aws s3 mv file-name s3://bucket-name`

Command to create a presigned URL: `aws s3 presign s3://DOC-EXAMPLE-BUCKET/test2.txt`

Command to delete your bucket with the AWS CLI: `aws s3 rb s3://bucket-name --force`

Can you simply delete a CloudFormation bucket? : `Yes, but the bucket must be empty before deleting it. We can use the rb (remove bucket) AWS CLI command with the --force parameter to delete the bucket and all the objects in it. This command deletes all objects first and then deletes the bucket.`

**Assignment 4 (Optional):**

Command to deploy your CloudFormation template using the AWS CLI: `aws cloudformation deploy --template-file /path_to_template/template.json --stack-name my-new-stack --parameter-overrides Key1=Value1 Key2=Value2 --tags Key1=Value1 Key2=Value2`
