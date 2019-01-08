# terraform_github_provider

### Purpose of the repository 
- The repository creates repository in GitHub oraganization for teams with approriate credentials. 

#### List of files in the repository

File name                            | File description 
------------------------------------ | --------------------------------------------------------------
`main.tf` | Terraform configuration file for creating the repo in your GitHub organization.


### SECURITY WARNING: THE FILE MENTIONED BELOW CONTAINS SENSITIVE INFORMATION, MAKE SURE THE FILE IS NOT EXPOSED TO THE INTERNET OR ANY OTHER PUBLIC PLACES.
- You need to create `filename.tfvars` file that has your GitHub organization token (file must have `.tfvars` extension). 
- Terraform will use the token in the file to create repository in your GitHub organization.
- The file must be local to your computer and to be uploaded to GitHub.
- To get your GitHub token follow this [instructions](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/)
- the file format should be as follow:

```
github_token = "token_from_GitHub"

```

### How to use this repository. 
- Install `terraform` by following this [instructions](https://www.terraform.io/intro/getting-started/install.html).
- Clone the repository to your local computer: `git clone git@github.com:nikcbg/terraform_github_provider`.
- Go to the cloned repo on your computer: `cd terraform__github_provider`.

### Commands needed to build and apply execution plan for the `github_provider` provider.

Command execution                    | Command outcome
------------------------------------ | --------------------------------------------------------------
`terraform init` | to initialize the working directory 
`terraform plan` | to create execution plan for changes to be applied. 
`terraform apply` | to apply the desired changes. 


### TO DO: 
- Check if everything works as expected. 
