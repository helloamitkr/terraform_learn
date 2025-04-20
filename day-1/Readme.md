# What is terraform

Terraform helps you write code to create and manage infrastructure (like servers, databases, storage) instead of doing it manually via a UI or CLI and using HCL (Hashicorp Configuration Language).

## Install Terraform
    ```
        terraform version
    ```

## Terraform Commands (lifecycle)
    ```
    terraform init
    terraform plan
    terraform apply
    terraform destroy
    ```
## HCL Basic Syntax

```
    block "block_type" "block_name"{
        arg = "value"
    }
```