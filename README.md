# AWSprojects
AWSprojects


Temporary Access Management  With IAM Roles Projects.

In this project i granted access to contract workers with a limited time condition and implemented a cleanup mechanism to automatically revoke access to the role after the specified time frame. Enhancing security and minimizing resource exposure.

CREATE AN IAM USER.
CREATE AN IAM ROLE WITH CUSTOM TRUST POLICY.
ADD PERMISSIONS TO READ ONLY ACCESS TO EC2 AND S3 FOR THE ROLE.
LOGIN INTO THE USER ACCOUNT AND ASSUME THE ROLE.

    
   - Create an IAM User Called "ContractorUser/Maniche2015@".
   - Provide user access to the AWS Management Console.
   - Select option Users must create a new password at next sign-in.
   - Now Create an IAM ROLE with Trust policy For the User created above and Add EC2 and S3 Read only access permission to the Role and create the ContractorRole.
   - Switch to a private window or another browser  and login into the Contractoruser account.
   - Click on user profile and click on switch role, then use the main Account ID and Role name to switch Role so the contractoruser can have his Readonly Access to both EC2 and S3.
     
   - The End. 

  
