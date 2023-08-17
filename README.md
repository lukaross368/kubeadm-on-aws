## Project Overview

#### Part 1: Build AWS Infrastructure with Terraform:

 - Setup Terraform Connection to AWS
 - Define Networking and Security Resources 
 - Define Compute Resources and Loadbalancers (Refer to Kubeadm docs for minimum requirments)
 - Bootstrap Compute Resoures with Ansible, Container Runtime, Kubeadm, Kubelet and Kubectl
 - Spin up and test Infrastructure

#### Part 2: Deploy Minimum Viable Kubernetes Cluster with Kubeadm and Ansible:

 - Setup Ansible Locally and test connection to Running EC2 Instances
 - Write Ansible Playbook for Kubeadm master node setup
 - Write Anisble Playbook to join worker nodes to control plane and enable Pod networking
 - Write Ansible Playbook to install and configure kubernetes metric server
 - Run Playbooks and validate results
