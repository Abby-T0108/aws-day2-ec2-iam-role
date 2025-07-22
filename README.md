aws-day2-ec2-iam-role
AWS Day 2 of 100 – EC2 Instance with IAM Role Attached

AWS Day 2 – IAM Role + EC2
Today’s task was to launch an EC2 instance and attach an IAM role that allows it to access AWS services securely.
What I Did:
•	Created a custom IAM Role with `AmazonS3ReadOnlyAccess`
•	Launched an EC2 instance and attached the IAM Role
•	Used `aws sts get-caller-identity` to verify the EC2 instance assumed the role

Screenshot
See the uploaded screenshot in this repo showing successful role assumption.
This is part of my #100DaysOfCloud journey, deploying real-world projects using AWS.
