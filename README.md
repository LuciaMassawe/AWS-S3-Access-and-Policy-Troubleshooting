# AWS-S3-Access-and-Policy-Troubleshooting
This project involves securely configuring an AWS S3 bucket with restricted access using bucket policies and IAM permissions. It includes simulating access denial by applying restrictive policies, then troubleshooting and restoring correct permissions to ensure proper access control and data protection.


**Project Goals**
- Create a private S3 bucket with all public access blocked.
- Enable bucket versioning to protect against accidental deletion.
- Upload test objects to the bucket.
- Verify baseline IAM user access to the bucket.
- Apply restrictive bucket/IAM policies that revoke access.
- Troubleshoot access denial issues caused by policy restrictions.
- Restore IAM permissions and confirm successful access.


## Technologies & Services Used
- Amazon S3  
- S3 Bucket Policies  
- IAM User Permissions  
- Bucket Versioning  
- AWS Management Console  


## Steps and Implementation
1. **S3 Bucket Creation**  
   Created a private S3 bucket (`project2-s3-policy`) with public access blocked and bucket versioning enabled.

2. **Uploading Test Object**  
   Uploaded sample files to simulate user data access.

3. **Baseline Access Verification**  
   Confirmed IAM user had access before applying any restrictive policies.

4. **Restrictive Policy Application**  
   Created and attached bucket/IAM policies that revoked access permissions for the IAM user.

5. **Access Denied Testing**  
   Verified the IAM user received “Access Denied” when trying to access the bucket.

6. **Troubleshooting**  
   Reviewed IAM and bucket policies to identify missing permissions causing the denial.

7. **Access Restoration**  
   Updated IAM permissions to restore required access, confirmed successful user operations.
   

**Outcomes and Learnings**
- Gained experience in secure bucket setup and policy enforcement.  
- Developed troubleshooting skills with S3 bucket policies and IAM permissions.  
- Learned best practices for protecting S3 data via versioning and access controls.

 [Project 2.docx](https://github.com/user-attachments/files/25691203/Project.2.docx)


  
