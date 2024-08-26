# Full Terraform Pipeline

This repository provides Github Actions YAML files containing a full terraform pipeline. This includes a test, plan, and apply steps going from PR to provisioning infrastructure.

## Features

The files in this repository contain the following steps (not in order):

- Setting up Terraform with a specific version
- Configure AWS credentials to provision infrastructure
- Initialise Terraform
- Terraform fmt check
- Terraform Test Framework
- Checkov testing
- Terraform validate
- Commenting test, plan, and apply results to open PRs
- Terraform plan
- Uploading and downloading artifacts
- Finally, applying Terraform

## Prerequisites

- An AWS account
- A GitHub account
- Terraform (version used is 1.9.2)
- An OIDC provider
- An AWS Role with proper permissions to deploy to AWS
- Basic knowledge of AWS, GitHub, and Terraform

## Usage

To make use of the pipeline, and to get more insight into how it works, please check out my website [here](https://www.adnanalshar.com/projects/full-terraform-pipeline/)