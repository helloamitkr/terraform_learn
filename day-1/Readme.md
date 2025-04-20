# What is terraform

Terraform helps you write code to create and manage infrastructure (like servers, databases, storage) instead of doing it manually via a UI or CLI and using HCL (Hashicorp Configuration Language).

## Install Terraform

    ```bash
    terraform version
    ```

## Terraform Commands (lifecycle)
    ```bash
    terraform init
    terraform plan
    terraform apply
    terraform destroy
    ```
## HCL Basic Syntax

```bash
    block "block_type" "block_name"{
        arg = "value"
    }
```