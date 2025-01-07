AWS CodeBuild CI/CD Pipeline with Terraform
This project demonstrates the configuration of a Continuous Integration and Continuous Deployment (CI/CD) pipeline using AWS CodeBuild and Terraform.

Project Structure
main.tf: Contains the main Terraform configuration.
variables.tf: Defines the input variables for Terraform.
outputs.tf: Specifies the outputs of the Terraform configuration.
buildspec.yml: Defines the build commands and settings for AWS CodeBuild.
README.md: Project documentation.
Prerequisites
AWS account with appropriate permissions.
Terraform installed on your local machine.
AWS CLI configured with your credentials.
Basic understanding of AWS CodeBuild and Terraform.
Setup Instructions
Clone the Repository:

git clone https://github.com/anjana2468/Terraform-AWS-CodeBuild-CICD-Pipeline.git
cd Terraform-AWS-CodeBuild-CICD-Pipeline
Initialize Terraform:

terraform init
Review and Apply the Terraform Configuration:

Plan the Deployment:

terraform plan
Apply the Configuration:

terraform apply
Note: Review the plan output carefully before applying.

Configure AWS CodeBuild:

Ensure that the buildspec.yml file is correctly set up to define the build commands and settings for your project.
Trigger the Build:

Initiate a build in AWS CodeBuild to start the CI/CD pipeline.
Application Usage
Monitoring Builds:

Navigate to the AWS CodeBuild console to monitor the status of your builds.
Managing Infrastructure:

Use Terraform commands to manage and update your infrastructure as code.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request.
