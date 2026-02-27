# Kubernetes-onprem-via-ansible
How to create a complete Kubernetes cluster in your own infrastructure using Ansible

## Minimum pre-requisites:

- 3 or more Linux Servers Ubuntu 22.04 or 24.04 (on-prem vm, on-prem physical, vm cloud.. etc)
- A linux terminal with ansible (master) configured
- Configure the 3 or more target Linux servers for the Kubernetes cluster in the Ansible master inventory
- Kubernetes cluster that will be created in this automation, version: 1.30.4
- For other Kubernetes versions, just change the version variable: `kubernetes_version: "1.30.4"`

In this Ansible project, is created a set of automations that allows us to create a complete Kubernetes cluster (control plane + workers) in an on-premises infrastructure with virtual servers (Linux VMs) or physical Linux servers in a datacenter.

Kubeadm oficial documentation: https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/

---

## How this Ansible playbook works

<img width="1842" height="955" alt="diagrama" src="https://github.com/user-attachments/assets/222c5b24-ed97-4d18-b826-869ac8c85e57" />


documentation in progress...

---
