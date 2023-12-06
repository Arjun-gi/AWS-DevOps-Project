# AWS-DevOps-Project
This comprises code for deployment and detail steps for reference.

AWS services: code commit, code build, code deploy, code pipeline, IAM, KMS, EC2, S3.

Steps:
1. create repository into AWS code commit.
2. create IAM user: to provide the HTTPS git credentials for AWS code commit.
     generate HTTPS credentials under security credentials of IAM user.
   ![image](https://github.com/Arjun-gi/AWS-DevOps-Project/assets/85561570/ee033ff6-34f5-4ddf-9245-9797d68d025d)

   also provide codecommit access to IAM user by attaching policy
   ![image](https://github.com/Arjun-gi/AWS-DevOps-Project/assets/85561570/e3765bea-0d2a-4f26-bb0d-e0d44c8e75a7)

3.Clone the codecommit repository into local IDE (VScode) by providing HTTPS generated credentials.
4.Add sample index.html file and push it into AWS code commit repository.

![image](https://github.com/Arjun-gi/AWS-DevOps-Project/assets/85561570/7dc98ad9-c679-4c25-a437-27c99a1e4c7a)






