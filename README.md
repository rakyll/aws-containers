# aws-containers

> There are 2 ways to _run_ containers in AWS: EC2 or Fargate. -- [Justin Garrison](https://twitter.com/rothgar/status/1397599865870295040)

But, there are many ways to orchestrate and schedule your containers,
and many tools to help you build and distribute containers.

## Orchestration

* [ECS](https://aws.amazon.com/ecs/)
* [ECS Fargate](https://aws.amazon.com/fargate/)
* [ECS Anywhere](https://aws.amazon.com/ecs/anywhere/)
* [EKS](https://aws.amazon.com/eks/)
* [EKS Fargate](https://aws.amazon.com/fargate/)
* [EKS Anywhere](https://aws.amazon.com/eks/eks-anywhere/)
* [AppRunner](https://aws.amazon.com/apprunner/)
* [Lambda](https://aws.amazon.com/blogs/aws/new-for-aws-lambda-container-image-support/) (containers need to implement the Lambda Runtime API)
* [Batch](https://aws.amazon.com/batch/)

## Image Distribution

* [ECR](https://aws.amazon.com/ecr/)
* [ECR Public](https://docs.aws.amazon.com/AmazonECR/latest/public/public-repositories.html)
* [Docker S3 Driver](https://docs.docker.com/registry/storage-drivers/s3/)

## Build and Deployment

* [Proton](https://aws.amazon.com/proton/)
* [App2Container](https://aws.amazon.com/app2container/)
* [Copilot](https://aws.github.io/copilot-cli/)

## Provisioning

* [eksctl](https://eksctl.io/)
* [CDK](https://aws.amazon.com/cdk/)
