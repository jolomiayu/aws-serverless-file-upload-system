🚀 AWS Serverless CI/CD File Upload System

📌 Project Overview

This project demonstrates a fully automated CI/CD pipeline that deploys a serverless file upload system on AWS.

Whenever code is pushed to GitHub, the pipeline automatically builds and deploys infrastructure using CloudFormation.

---

🏗️ Architecture

This project uses a serverless architecture:

- Amazon S3 → stores uploaded files
- AWS Lambda → processes uploads
- Amazon DynamoDB → stores metadata
- AWS CodePipeline → automates deployment
- AWS CodeBuild → builds the application
- AWS CloudFormation → provisions infrastructure

---

⚙️ How It Works

1. Code is pushed to GitHub
2. CodePipeline is triggered automatically
3. CodeBuild runs buildspec.yml
4. CloudFormation deploys infrastructure
5. S3 upload triggers Lambda
6. Lambda stores metadata in DynamoDB

---

🛠️ Technologies Used

- AWS CodePipeline
- AWS CodeBuild
- AWS CloudFormation
- AWS Lambda
- Amazon S3
- Amazon DynamoDB

---

📸 Screenshots

CodePipeline

"CodePipeline" (./project-4-screenshots/1-codepipeline.png)

CodeBuild

"CodeBuild" (./project-4-screenshots/2-codebuild.png)

CloudFormation

"CloudFormation" (./project-4-screenshots/3-cloudformation.png)

S3 Bucket

"S3" (./project-4-screenshots/4-s3.png)

Lambda Function

"Lambda" (./project-4-screenshots/5-lambda.png)

DynamoDB Table

"DynamoDB" (./project-4-screenshots/6-dynamodb.png)

---

📂 Project Structure

.
├── buildspec.yml
├── template.yaml
├── lambda_function.py
└── README.md

---

🎯 Key Features

- Fully automated CI/CD pipeline
- Infrastructure as Code (CloudFormation)
- Event-driven serverless architecture
- Scalable and cost-efficient

---

📈 What I Learned

- Building CI/CD pipelines on AWS
- Automating infrastructure deployment
- Integrating multiple AWS services
- Real-world DevOps workflow

---

👨‍💻 Author

Jolomi Ayu
AWS Cloud Engineer (Entry-Level)
