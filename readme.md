# Setup cluster with Kubeadm and containerd

## Benefit of clustering

## Requiment

## Install kube
- Download the latest release with the command:
```bash
   curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"

```
- Install kubectl (in master or both)
```bash
sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
```