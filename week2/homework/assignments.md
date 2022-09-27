## Mandatory assignments

**Assignment 4 & 5:**

Sync your changes to s3 and write down your s3 bucket url.

bucket url: `aws s3api create-bucket --bucket hyf-hosting-shruthi --region us-east-1`

**Assignment 6:**

Right now, the website does not support HTTPS. Explain which other AWS service needs to be integrated in order to achieve this.

service name: `cloudFront`

**Assignment 7:**

Write down the main cost factors for S3

brief description: `S3 costs depend on the request type (e.g. PUT, COPY, GET, etc.), the number of requests, and the volume of data retrieved. For example, 1,000 GET requests to a Glacier tier costs only $0.0004, but 1,000 PUT requests to the same tier costs 125 times as much ($. 05) and adds up much more quickly.`

The main factors that effect the Amazon s3 pricing:

The region where you store your data
The volume of data you store
The level of redundancy
The storage class
Data requests
Data transfers
Data retrievals

**Assignment 8:**

How much would it cost to store 51TB on S3?
Frequent Access Tier, First 50 TB / Month $0.023 per GB
S3 Standard Storage $ 1200.13
Support for all AWS services: $ 120.01
Total Monthly Payment: $ 1320.02

Price: `1200.13 $`

**Assignment 9:**

How much would hosting your website on S3 cost?

The total cost of hosting your personal website on AWS will vary depending on your usage. Typically, it will cost $1-3/month if you are outside the AWS Free Tier limits. If you are eligible for AWS Free Tier and within the limits, hosting your personal website will cost around $0.50/month.

Price: `$0.50/month`

**Assignment 10:**

Write down a brief use case on when S3 could be used for a data engineering assignment:

use case: `Amazon S3 is commonly used in AWS Data Engineering for Data Storage from multiple sources because it’s a highly scalable, fast, cost-effective solution. S3 stores data in Objects, which are fundamental entities that consist of data and its metadata. Objects stores pairs where metadata is the description of respective data like Date has Date-Time description. With AWS Data Engineering, Amazon S3 allows you to run Big Data Analytics for better insights`

## Optional assignments:

**Assignment 11:**

What can be done to reduce the pricing for S3 when hosting a large number of files?

brief description: `?`

**Assignment 12:**

There are many security features built into S3. Find your favourite feature, documentation for it, and explain briefly why.

brief description of favourite security feature: `?`
