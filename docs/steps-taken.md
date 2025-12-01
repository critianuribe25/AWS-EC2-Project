# Steps Taken — EC2 Deployment

1. Navigated to the EC2 Console.
2. Clicked **Launch Instance** and named the instance `my-ec2-project`.
3. Selected **Amazon Linux 2 (Free Tier)**.
4. Selected instance type **t2.micro**.
5. Created a new key pair for SSH authentication.
6. Configured security group:
   - Allowed SSH (22) from My IP only
7. Launched the instance.
8. Waited for **Status Checks: 2/2 passing**.
9. Connected to the instance via SSH.
10. Ran verification commands:
    - `uname -a`
    - `ls -al`
    - `curl google.com`
