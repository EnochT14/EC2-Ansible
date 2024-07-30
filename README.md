- Creates a security group named your-security-group with rules allowing SSH (port 22), HTTP (port 80), and HTTPS (port 443) traffic from anywhere.
- Launches an EC2 instance using the specified AMI ID, instance type, and key pair.
- Ensures the instance has a public IP address.
- Creates an S3 bucket named your-unique-s3-bucket.

## Prerequisites
- An AWS account with IAM permissions to create EC2 instances, S3 buckets, and security groups.
- Configure your AWS credentials using the AWS CLI or environment variables.

## Usage
1. Run it using the following command
```
ansible-playbook ec2.yml
```
