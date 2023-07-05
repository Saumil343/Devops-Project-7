# Devops-Project-7

Project Description:
This workshop focuses on implementing a CI/CD pipeline using GitHub and various AWS services.
you will learn how to deploy the latest web application code from GitHub to an Apache server running on an AWS EC2 instance.
The workshop demonstrates the seamless integration of version control, automated builds, and deployment processes.

- <b> PROJECT LIFECYCLE </b>

- ![devops project 6 drawio](https://user-images.githubusercontent.com/53990452/188196586-5d968cec-891f-4d4c-83dc-ca106fa69939.png)


<b> Project Description </b>
- The Project Uses concepts of CI/CD along with github to deploy the latest web app code from github to apache server on aws ec2 instance.
- <b> Technologies Used </b>
1)  Github
2) AWS Code Pipeline
3) AWS Code Build
4) AWS ec2 Instance




 - <b>  Creating IAM role to attach to EC2 instance </b>
 -  Policies In the IAM Role :
 -  ![image](https://user-images.githubusercontent.com/53990452/188197786-359ced6d-987d-42e9-beb0-42546eb22e85.png)


- <b> Creating IAM role to attach to AWS CODE DEPLOY </b>
-  Policies in the IAM Role :
-  ![image](https://user-images.githubusercontent.com/53990452/188199120-9c6dacf6-d179-4c30-8818-6224df8f1abf.png)





- <b> Creating AWS CODE DEPLOY  APPLICATION  AND DEPLOYMENT GROUPS </b> 
- ![Screenshot (101)](https://user-images.githubusercontent.com/53990452/188200145-699f2cc3-b220-441b-85d3-bf3e652aadb7.png)
- ![Screenshot (102)](https://user-images.githubusercontent.com/53990452/188200155-6e5929e7-d6c2-497a-8bd2-37664feb6db0.png)
- ![Screenshot (103)](https://user-images.githubusercontent.com/53990452/188200159-4f956e54-6d7c-461f-9e2a-a27f9a08155d.png)
- ![Screenshot (104)](https://user-images.githubusercontent.com/53990452/188200161-692988f2-b125-4566-b5cb-20b8fc94d7a2.png)


- <b> Creating AWS CODE PIPELINE TO DEPLOY FROM GITHUB TO CODE DEPLOY</b>
![Screenshot (105)](https://user-images.githubusercontent.com/53990452/188200979-2eee9c7a-1a2f-4c9d-8e76-a5339d85f781.png)
![Screenshot (106)](https://user-images.githubusercontent.com/53990452/188200984-69f94ad2-0e2c-4ba5-b47f-592d7757ee84.png)
![Screenshot (107)](https://user-images.githubusercontent.com/53990452/188200987-9111bb2b-ebe6-46ac-b902-722287c10581.png)
![Screenshot (108)](https://user-images.githubusercontent.com/53990452/188200994-30453de3-ede4-4039-8a82-67678dfc5983.png)
![Screenshot (109)](https://user-images.githubusercontent.com/53990452/188200996-0662f944-5c2c-431a-b1a4-5f962ce66b79.png)
![Screenshot (110)](https://user-images.githubusercontent.com/53990452/188200998-d61bde54-cdeb-4e06-b61e-13c89c7bcdc3.png)
![Screenshot (111)](https://user-images.githubusercontent.com/53990452/188201000-563ece15-d35a-4054-8d08-a54ffd6a5f7b.png)

<b> DOCUMENTATIONS WHICH HELPED TO RESOLVE ERRORS </b>
- https://docs.aws.amazon.com/codedeploy/latest/userguide/codedeploy-agent-operations-install-linux.html
- https://aws.amazon.com/premiumsupport/knowledge-center/codedeploy-agent-non-root-profile/
- https://docs.aws.amazon.com/codedeploy/latest/userguide/reference-appspec-file.html
