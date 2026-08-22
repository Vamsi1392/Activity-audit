
# EX - 4 Auditing Cloud Activity Using AWS CloudTrail

## Aim

To enable and analyze AWS CloudTrail logs to audit user and resource activities in a cloud environment.

## Requirements
1. AWS Console access
2. CloudTrail service enabled
3. S3 bucket (for storing logs)
4. IAM permissions to view audit logs

## Procedure

### Step 1: Login to AWS
1.	Open the AWS Management Console. 
2.	Sign in using your AWS account. 
3.	Search for S3. 
4.	Select Amazon S3. 

### Step 2: Select the S3 Bucket
1.	Click Buckets. 
2.	Select the S3 bucket created in the previous experiment. 

### Step 3: Check Block Public Access
1.	Open the S3 bucket. 
2.	Select Permissions. 
3.	Locate Block public access (bucket settings). 
4.	Check Block all public access.

### Step 4: Check Bucket Versioning
1.	Select the Properties tab. 
2.	Locate Bucket Versioning. 
3.	Record whether it is: 
        o	Enabled 
        o	Disabled 
### Step 5: Check Default Encryption
1.	Stay in the Properties tab. 
2.	Locate Default encryption. 
3.	Record the encryption type.

### Step 6: Check Bucket Policy
1.	Select Permissions. 
2.	Locate Bucket policy. 
3.	Check whether a bucket policy exists. 

### Step 7: Check Object Ownership and ACL
1.	In Permissions, locate Object Ownership. 
2.	Record the current configuration.

### Step 8: Check Server Access Logging
1.	Go to Properties. 
2.	Locate Server access logging.

## Output:

### S3 Bucket
<img width="1920" height="1200" alt="Screenshot 2026-08-22 141258" src="https://github.com/user-attachments/assets/c720c872-32c2-417d-ac40-ca680110b2b6" />

### Block Public Access
<img width="1920" height="1200" alt="Screenshot 2026-08-22 140050" src="https://github.com/user-attachments/assets/82aafd83-bcf3-46cc-ae61-af9f8bd4cbdd" />

### Bucket Versioning
<img width="1920" height="1200" alt="Screenshot 2026-08-22 141212" src="https://github.com/user-attachments/assets/2787f47f-517b-4d22-884e-ba51c1cdc403" />

### Default Encryption
<img width="1920" height="1200" alt="Screenshot 2026-08-22 141418" src="https://github.com/user-attachments/assets/55309173-b9e2-49c3-9679-e9611a585573" />

### Bucket Policy
<img width="1920" height="1200" alt="Screenshot 2026-08-22 141554" src="https://github.com/user-attachments/assets/7bff5520-af5d-4efa-bc07-cac807e961a6" />

### Object Ownership and ACL
<img width="1920" height="1200" alt="Screenshot 2026-08-22 141629" src="https://github.com/user-attachments/assets/30af6bff-0d02-492d-9945-9195839e3a1e" />

### Server Access Logging
<img width="1915" height="840" alt="Screenshot 2026-08-22 141746" src="https://github.com/user-attachments/assets/0dd99cd2-4156-4a1f-839c-706b4a7a430c" />

## Result

All AWS user activities, including volume creation, deletion, and permission changes, were successfully audited using CloudTrail.

