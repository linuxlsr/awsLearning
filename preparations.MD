The goal of this exercise is to convert my personal account to an organization structure with different accounts for
environments, and lay the ground work for a multi environment deployments of various infrastructure patterns.

Once organized and IAM roles are complete, the next step is to put in the resources to support terraform deployed by
github actions.

Convert personal account to organization with accounts for diff envs

- added organization in main account
- created via GUI sandbox account
- https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/organizations_organization

Add IAM roles to accounts for admin switching