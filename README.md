# 2-13
Serverless Framework vs Terraform
1. What type of infrastructure and application deployments are each tool best for?
Serverless Framework: Best for serverless apps like AWS Lambda, API Gateway, DynamoDB.

Terraform: Best for full cloud infrastructure — VMs, databases, networks, etc.

2. How do their goals differ?
Serverless: Focuses on deploying serverless functions quickly.

Terraform: Manages and automates all types of cloud infrastructure.

3. Learning curve and ease of use?
Serverless: Easier for developers; good for fast deployments.

Terraform: More complex; better for DevOps and big setups.

4. How do they handle state and deployment changes?
Serverless: Limited state tracking, usually replaces resources.

Terraform: Keeps a state file, tracks changes, and updates only what’s needed.

5. When to use one over the other?
Use Serverless if:

You’re building serverless functions.
You want quick and simple deployments.

Use Terraform if:

You’re managing lots of infrastructure.
You need multi-cloud or detailed control.

6. Can you use both?
Yes. Use Terraform to set up infrastructure, then use Serverless to deploy your app.
