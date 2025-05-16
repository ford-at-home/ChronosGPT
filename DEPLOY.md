# DEPLOY.md

## Deploying to AWS

### Requirements
- AWS CLI configured
- Amazon Connect instance
- EC2 instance or Lambda for backend hosting

### Steps
1. Deploy backend to EC2 using Docker
2. Set up Amazon Connect and configure routing profiles
3. Store Google credentials in AWS Secrets Manager
