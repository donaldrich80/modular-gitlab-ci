---
title: Terraform
path: tree/master
source: function/hashicorp/terraform.yml
---

# Terraform

## Usage

Required Variables:

```yaml
variables:
  TERRAFORM_PATH: # path to .tf file
```

include in `.gitlab-ci.yml`

```yaml
include:
  - project: donaldrich/modular-gitlab-ci
    file: function/hashicorp/terraform.yml
```

## Documentation

## Links

- [:octicons-mark-github-16: wardviaene/terraform-course](https://github.com/wardviaene/terraform-course)

- [:octicons-mark-github-16: hashicorp/terraform-guides](https://github.com/hashicorp/terraform-guides)

- [:octicons-mark-github-16: PaloAltoNetworks/terraform-templates](https://github.com/PaloAltoNetworks/terraform-templates)

- [https://hub.docker.com/r/simonmcc/hashicorp-pipeline/dockerfile](https://hub.docker.com/r/simonmcc/hashicorp-pipeline/dockerfile)

- [https://github.com/in4it/terraform-modules](https://github.com/in4it/terraform-modules)

## Providers

### :octicons-plug-16: DNS

- [:octicons-plug-16: GitHub](https://github.com/hashicorp/terraform-provider-dns)

### :octicons-plug-16: Proxmox

- [:octicons-plug-16: GitHub](https://github.com/Telmate/terraform-provider-proxmox)

### :octicons-plug-16: Cloudflare

- [:octicons-mark-github-16: GitHub](https://github.com/cloudflare/terraform-provider-cloudflare)

- [:octicons-mark-github-16: Docs](https://registry.terraform.io/providers/cloudflare/cloudflare/latest/docs)

### :octicons-plug-16: GitLab

- [:octicons-plug-16: GitHub](https://github.com/terraform-providers/terraform-provider-gitlab)

- [:octicons-plug-16: terraform-provider-keycloak](https://github.com/mrparkers/terraform-provider-keycloak)

- [:octicons-plug-16: terraform-provider-docker](https://github.com/terraform-providers/terraform-provider-docker)

- [:octicons-plug-16: terraform-provisioner-ansible](https://github.com/radekg/terraform-provisioner-ansible)

- [:octicons-plug-16: terraform-provisioner-ansible](https://github.com/jonmorehouse/terraform-provisioner-ansible)

- [:octicons-plug-16: terraform-provider-influxdb](https://github.com/terraform-providers/terraform-provider-influxdb)
