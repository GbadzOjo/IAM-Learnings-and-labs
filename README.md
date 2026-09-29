# IAM-labs
The introductory class covered identity and access management using group policies to allow or restrict objects (users) from accessing resources.
This is a reproduction of the class activity to enforce a least-privilege policy. 
An S3 bucket, policy, and user group were created. A user was also created and assigned to the user group that had a policy assigned to test the permissions available to the user.
The S3 bucket
<img width="944" height="419" alt="Screenshot 2026-09-25 122649" src="https://github.com/user-attachments/assets/765e2941-fd97-4e5e-b6fc-4c2b5606a5e4" />
The policy was created in the IAM console, and a user group was also created
<img width="1919" height="874" alt="Screenshot 2026-09-25 123654" src="https://github.com/user-attachments/assets/1da7e178-fcd2-412e-9cea-bac6d09e5a28" />
<img width="1896" height="775" alt="Screenshot 2026-09-25 124104" src="https://github.com/user-attachments/assets/d0dfa209-9cb3-4d98-be93-49afc8649267" />
Signed in as the user in another browser to test the policy enforcement. User Alice is unable to see the S3 bucket list based on the policy assigned
<img width="1913" height="805" alt="Screenshot 2026-09-25 125559" src="https://github.com/user-attachments/assets/c03a2689-c876-457c-a8c7-4a2c6dc697ee" />
Re-edited the policy to allow the user to see the bucket and upload to the bucket, and the user was able to 
<img width="1899" height="821" alt="Screenshot 2026-09-27 170856" src="https://github.com/user-attachments/assets/bfd420c7-cb68-41cd-a4bb-39c65c3d316a" />
<img width="1897" height="867" alt="Screenshot 2026-09-27 171012" src="https://github.com/user-attachments/assets/7c3e4f74-97e1-471c-babb-173507190319" />

