# First Terraform Project

Prequisites

- Terraform should be installed
- aws-cli should be installed and configured


There are two terraform projects, one is inside local_state and another is inside remote_state

To Execute any project, start by initializing terraform based on main.tf
```
terraform init
```

To dry run the infrastructure before creating, use the below command

```
terraform plan
```

To start infrastructure creation use 
```
terraform apply
```

To destroy infrastructure managed by terraform use 
```
terraform destroy
```
