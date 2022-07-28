# Tolkubernetes

Tolki's Kubernetes cluster definition

Based on [this template](https://github.com/k8s-at-home/flux-cluster-template/)

## Overview

<!-- TODO -->

## Apps

### Echo Server

`nginx` echo server.

### Hajimari

Home page.

### Calibre

Ebooks manager.
<!-- TODO -->

### Nextcloud

Cloud storage and chat.
<!-- TODO -->

## Tools

- [k3s](https://k3s.io/) - Lightweight Kubernetes
- [flux](https://toolkit.fluxcd.io/) - GitOps operator for managing Kubernetes clusters from a Git repository
- [kube-vip](https://kube-vip.io/) - Load balancer for the Kubernetes control plane nodes
- [metallb](https://metallb.universe.tf/) - Load balancer for Kubernetes services
- [cert-manager](https://cert-manager.io/) - Operator to request SSL certificates and store them as Kubernetes resources
- [calico](https://www.tigera.io/project-calico/) - Container networking interface for inter pod and service networking
- [external-dns](https://github.com/kubernetes-sigs/external-dns) - Operator to publish DNS records to Cloudflare (and other providers) based on Kubernetes ingresses
- [k8s_gateway](https://github.com/ori-edge/k8s_gateway) - DNS resolver that provides local DNS to your Kubernetes ingresses
- [ingress-nginx](https://kubernetes.github.io/ingress-nginx/) - Kubernetes ingress controller used for a HTTP reverse proxy of Kubernetes ingresses
- [local-path-provisioner](https://github.com/rancher/local-path-provisioner) - provision persistent local storage with Kubernetes
<!--
TODO
- [kubernetes-dashboard]
TODO
- [grafana]
-->
