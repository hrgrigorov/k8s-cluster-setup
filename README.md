# k8s-cluster-setup

This repo contains configuration scripts for Kubernetes cluster setup, for CentOS7
Setup instruction:
 1) run docker-setup.sh for installation and configuration on docker engine. This script should be ran on all nodes (in my case one control node and two worker nodes) 
 2) run k8s-setup.sh for installation and configuration on Kubernetes. This script should be ran on all nodes as well.
 3) run "kubeadm init" onto the control node and follow the instructions at the end of the installation
 4) run "kubectl cluster-info" and "kubectl get nodes" from the control node to verify that workers are joined into the cluster.
   
