**Note**: This public repo contains the documentation for the private GitHub repo <https://github.com/gruntwork-io/module-ecs>.
We publish the documentation publicly so it turns up in online searches, but to see the source code, you must be a Gruntwork customer.
If you're already a Gruntwork customer, the original source for this file is at: <https://github.com/gruntwork-io/module-ecs/blob/master/examples/docker-fargate-service-with-nlb/README.md>.
If you're not a customer, contact us at <info@gruntwork.io> or <http://www.gruntwork.io> for info on how to get access!

# Docker Fargate Service with NLB example

This folder shows an example of how to use the ECS modules to:

1. Deploy an ECS cluster
1. Deploy an NLB that can be shared among many Fargate Services
1. Run a simple "Hello, World" web service Docker container as a Fargate service
1. Use an NLB to route traffic to the Fargate service

## How do you run this example?

To run this example, simply apply the Terraform templates.

### Apply the Terraform templates

To apply the Terraform templates:

1. Install [Terraform](https://www.terraform.io/), minimum version: `0.6.11`.
1. Open `vars.tf`, set the environment variables specified at the top of the file, and fill in any other variables that don't have a default.
1. Run `terraform init`.
1. Run `terraform apply`.