## Mandatory assignments

**Assignment 1:**

Three line sample of the S3 access logs for your bucket:

```
02ab59be071f966e7118ee3abae63d146f159c00c29f34224630f3f8bb8be24d hyf-hosting-shruthi [03/Oct/2022:09:27:28 +0000]-
svc:s3.amazonaws.com HQ39SJZRWCKR51KK REST.PUT.OBJECT logs2022-10-03-09-27-28-75362FD33678124B
"PUT /hyf-hosting-shruthi/logs2022-10-03-09-27-28-75362FD33678124B HTTP/1.1" 200 - - 632 71 44 "-" "-" -
b8Ie0imMcpvzfuaWjBRCbxiGiueZlWiAQ1l4j1dVdWH2tfJ5OAiqJGZgFChysMmxonPCvfSslPw= SigV4 ECDHE-RSA-AES128-GCM-SHA256 AuthHeader s3.us-east-1.amazonaws.com TLSv1.2 -

```

How would you calculate total impressions based on the S3 access logs format?

Bucket Owner: `02ab59be071f966e7118ee3abae63d146f159c00c29f34224630f3f8bb8be24d`
Bucket : `hyf-hosting-shruthi`
Time : `[03/Oct/2022:09:27:28 +0000]`
Remote IP : `87.72.238.219`
Requester : `02ab59be071f966e7118ee3abae63d146f159c00c29f34224630f3f8bb8be24d`
Request ID : `HQ39SJZRWCKR51KK`
Operation : `REST.PUT.OBJECT`
Key : ``Request-URI :`PUT /hyf-hosting-shruthi/logs2022-10-03-09-27-28-75362FD33678124B HTTP/1.1`HTTP status :`200`Error Code :`no error occured`Bytes Sent :`0`Object Size :`632 71 44`Host Id :`b8Ie0imMcpvzfuaWjBRCbxiGiueZlWiAQ1l4j1dVdWH2tfJ5OAiqJGZgFChysMmxonPCvfSslPw`Signature Version:`SigV4`Cipher Suite:`ECDHE-RSA-AES128-GCM-SHA256`Authentication Type:`AuthHeader`Host Header :`s3.us-east-1.amazonaws.com`TLS version :`TLSv1.2`Access Point ARN (Amazon Resource Name):`not used`

**Assignment 2:**

1. The URL of the public API: `https://zd7jftyc2h.execute-api.us-east-1.amazonaws.com/Prod/products`
2. The URL of the website using the API: `http://hyf-hosting-shruthi.s3-website-us-east-1.amazonaws.com`
3. Screenshot of the updated service map: `https://user-images.githubusercontent.com/66563360/195438122-0cce80fd-1d75-4c4a-874d-7664bd00bcd5.PNG`
4. Which service has the highest latency: `API-Gateway`

**Optional assignment**

1. Screenshot of the layer in the AWS console, clearly showing the ARN: `https://user-images.githubusercontent.com/66563360/195438171-a2e8bcfa-83ba-47d2-a899-8f51aa942c31.PNG`
2. Screenshot of the lambda function, clearly showing that it is now using the created layer: `?`
