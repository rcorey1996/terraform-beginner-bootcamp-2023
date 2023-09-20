# Terraform Beginning Bootcamp 2023 - Week 0

- [Sesmantic Versioning] (#semantic-versioning)
- [Install the Terraform CLI] (#install-the-terraform-cli)
  * [Considerations with the Terraform CLI changes] (#considerations-with-the-terrafor-cli-changes)
  * [Execution Considerations] (#execution-consideration)
  * [Refactoring into Bash Scripts] (#refactoring-into-bash-scripts)
    + [Shebang Considerations] (#shebang-consideration)
    + [Execution Considerations] (#execution-consideration)
    + [Linus Permissions-consderations] (#linux-permissions-considerations)
- [Gitpod Lifecycle] (#gitpod-lifecucles)
- [Working Env Var] (#working-rnv-var)
  * [env command] (#env-command)
  * [Setting and Unsetting Env Var] (#setting-and-unsetting-env-var)
  * [Printing Vars] (#printing-vars)
  * [Scoping of Env Vars] (#scoping-of-env-vars)
  * [Persisting Env Vars in Gitpod] (#persisting-env-vars-in-gitpod)
- [AWS CLI Installation] (#aws-cli-installation)
- [Terraform Basics] (#terraform-basics)
  * [Terraform Registry] (#terraform-registry)
  * [Terraform Console] (#terraform-console)
    + [Terraform Init] (#terraform-init)
    + [Terrafom Plan) (#terraform-plan)
    + [Terraform Apply] (#terraform-apply)
    + [Terraform Destroy] (#terraform-destroy)
    + [Terraform Lock Files] (#terraform-lock-files)
    + [Terraform State Files] (#terraform-state-files)
    + [Terraform Directory] (#terraform-directory)
 - [Issues with Terraform Cloud Login and Gitpod Workspace] (#issues-with-terrafom-cloud-login-and-gitpod-workspace)

## Sesmantic Versioning

This project is going to utilize semantic versioning for its tagging.
[semver.org] (https://senmver.org)

The general format:
 
 **MAJOR,MINOR,PATCH**, e.g. '1.0.1'

 - **MAJOR** version when you make imcompatable API changes
 - **MINOR** version when you add additional functionality in a backwork compatable manner
 - **PATCH** version when you make compatable bug fixes

## Install the Terraform CLI

### Considerations with the Terraform CLI changes
The Terraform CLI installation instructions have changed due to gpg keyring changes. So we needed to refer to the latest install CLI instructions via the Terraform Documentation and change the scripting to install.

[Install Terraform CLI] (https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)


### Considerations for Linux Distribution

This project is built against Ubunutu.
Please consider checking your Linux Distribution and change accordingto distribution needs.

