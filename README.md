# ECS-AWS-Github-actions

This repository contains a sample project that demonstrates how to use GitHub Actions to build and deploy a containerized application to Amazon Elastic Container Service (ECS).

## Getting Started

To get started, you will need to:

1. Create an Amazon ECR repository to store your images.
2. Create an Amazon ECS cluster and service.
3. Store your Amazon ECS task definition as a JSON file in your GitHub repository.
4. Create GitHub Actions secrets named AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY to store the values for your Amazon IAM access key.

## Workflow

The GitHub Actions workflow for this project is as follows:

1. On every push to the main branch, the workflow will build the container image and push it to Amazon ECR.
2. The workflow will then deploy the new container image to Amazon ECS.

## Troubleshooting

If you are having trouble getting this project to work, please see the following troubleshooting tips:

* Make sure that you have the correct AWS credentials stored in your GitHub Actions secrets.
* Make sure that your Amazon ECR repository, cluster, and service are configured correctly.
* Make sure that your Amazon ECS task definition is valid.

## Contributing

I welcome contributions to this project. If you would like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

If you have any questions, please contact me at [here](ayantolaibraheemkehinde@gmail.com)
