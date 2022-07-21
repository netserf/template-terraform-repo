# template-terraform-repo

[![Actions Status](https://github.com/netserf/template-terraform-repo/workflows/Terraform%20Lint/badge.svg)](https://github.com/netserf/template-terraform-repo/actions)
[![Actions Status](https://github.com/netserf/template-terraform-repo/workflows/Docs/badge.svg)](https://github.com/netserf/template-terraform-repo/actions)

Template repo for a Terraform build project.

## Build Environment

These instructions assume you already have Google Cloud access and you're
working in the Cloud Shell. From here clone the repo and follow the build steps
below.

```bash
git clone https://github.com/netserf/template-terraform-repo.git
```

## Build Steps

```bash
cd terraform
export GOOGLE_CLOUD_PROJECT=[project-id]
```

Pull the providers:

```bash
terraform init
```

Apply the updates:

```bash
terraform apply
```

## Clean Up

```bash
terraform destroy
```
