# IAC [ Infrastructure as Code]

## Terraform

Rename `terraform.tfvars.txt` to `terraform.tfvars` and edit the configurations.
then RUN these commands

```bash
terraform init
terraform plan
terraform apply
---
terraform destroy
```

## Ansible

Reaname `hosts.txt` to `hosts` and edit the configurations then Run these commands

```bash
ansible {hosts} -i /path/to/hosts -m ping
# ansible ec2 -i /path/to/hosts -m ping

ansible-playbook -i /path/to/hosts script.yaml

```