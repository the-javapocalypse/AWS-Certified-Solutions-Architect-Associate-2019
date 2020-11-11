# CloudFormation
---

AWS CloudFormation provides a common language for you to model and provision AWS and third party application resources in your cloud environment. AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all regions and accounts. This gives you a single source of truth for your AWS and third party resources.

Cloudformation Quickstart is a bunch of cloudformation templates already built by aws solution architects allowing you to create Complex environments very quickly


## Stacksets
Create, Update or delete stacks accross multiple accounts and regions with a single operation
Need admin account to create stacksets
Trusted accounts can create update or delete stack instances from stackset
When you update a stackset, all the associates stacks are updated throughout all accounts and regions

##### Q: Are there limits to the number of templates or stacks?

There are no limits to the number of templates. Each AWS CloudFormation account is limited to a maximum of **200 stacks**.

#####  Q: Are there limits to the size of description fields?

Template, Parameter, Output, and Resource description fields are limited to **4096 characters**.

##### Q: Are there limits to the number of parameters or outputs in a template?

You can include up to **60 parameters** and **60 outputs** in a template.
