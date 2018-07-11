# hygieia-k8s-cluster

This repository is the near-simplest example of deploying an provisioning a web server on Amazon Web Services (AWS), using [Terraform](https://www.terraform.io/) and [Ansible](http://docs.ansible.com/ansible/).
- P.S.: It is incomplete. Just working OpenVPN. You will need execute manually. Before you will need edit vars.tf with your credencials and keys. After that follow the steps bellow:
```sh
git clone
cd terrAS
./deploy.sh
```

## Setup

1. Connect to Kubernetes cluster (AWS, GCP, etc.)
2. ./deploy-kubernetes
```sh
./deploy.sh
```
