# Ansible Kubernetes Setup Playbook

This lab contains Ansible roles and playbooks for provisioning and deploying Kubernetes clusters using Ansible.

There are roles for installing components like kubectl, kubeadm, kubelet, containerd, and also configuring network needed for Kubernetes.

## Repository Structure

The repository structure is organized as follows:

- `inventory/`: Directory containing inventory files for specifying your Kubernetes hosts.
- `roles/`: Directory containing reusable Ansible roles used by the playbooks.
- `site.yml`: Serves as the central playbook where you import playbooks needed.