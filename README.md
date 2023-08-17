## Project Overview

#### Part 1: Build AWS Infrastructure with Terraform:

 - Setup Terraform Connection to AWS
 - Define Networking and Security Resources 
 - Define Compute Resources and Loadbalancers (Refer to Kubeadm docs for minimum requirments)
 - Bootstrap Compute Resoures with Ansible, Container Runtime, Kubeadm, Kubelet and Kubectl
 - Spin up and test Infrastructure

#### Part 2: Deploy Kubernetes cluster with Kubeadm and Ansible:

 - Setup Ansible Locally and test connection to Running EC2 Instances
 - Write Playbook for Kubeadm master node setup
 - Write Playbook to join worker nodes to control plane and enable Pod networking
 - Write Playbook to install and configure kubernetes metric server
 - Run Playbooks and validate results

#### Part 3: Deploy static HTML application with nginx web server

 - Write Playbook to deploy Static HMLT application to pods across the cluster
 - Verify the deploy
