# Kubernetes-onprem-via-ansible
How to create a complete Kubernetes cluster in your own infrastructure using Ansible

## Minimum pre-requisites:

- 3 or more Linux Servers Ubuntu 22.04 or 24.04 (on-prem vm, on-prem physical, vm cloud.. etc)
- A linux terminal with ansible (master) configured
- Configure the 3 or more target Linux servers for the Kubernetes cluster in the Ansible master inventory
- Kubernetes cluster that will be created in this automation, version: 1.30.4
- For other Kubernetes versions, just change the version variable: `kubernetes_version: "1.30.4"`


In this Ansible project, I created a set of automations that allows us to create a complete Kubernetes cluster (control plane + workers) in an on-premises infrastructure with virtual servers (Linux VMs) or physical Linux servers in a data center.

This automation works similarly to what cloud providers do today when we request a new AKS (Azure), EKS (AWS), GKE (Google Cloud), but in this case, we can set up our own cluster on our own Linux servers.


Kubeadm oficial documentation: https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/


---

# How this Ansible playbook works

<img width="1842" height="955" alt="kubernetes-ansible" src="https://github.com/user-attachments/assets/42cac189-f187-435c-ab6e-208fcd8f8609" />
