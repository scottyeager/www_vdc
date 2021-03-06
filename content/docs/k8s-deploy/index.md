---
description: ''
sidebar: 'docs'
prev: '/docs/start-pay/'
next: '/docs/k8s-upload/'
---

# Deploy K8s Cluster

A Kubernetes cluster comes with the creation of your VDC. 

- This deployment creates a K3s Lightweight Kubernetes implementation in Zero-OS

  ![](./img/logo-k3s.png)
- K3s is a full conformant production-ready Kuberrnetes distribution with the following changes:   
   - It is packaged as a single binary
   - It adds support for sqlite3 as default storage. Etcd3, MySQL and Postgres are also supported
   - It wraps Kubernetes and other components in a single, simple launcher
   - It is secure by default with reasonable defaults for lightweight environments
   - It eliminates the need to expose a port on Kubernetes worker nodes for the kubelet API by exposing this API to the Kubernetes control plane nodes over a websocket tunnel.
   
  More info on K3s can be found at it's [Github repository](https://github.com/rancher/k3s).
   
- You'll need to log in through ThreeFold Connect, an authenticator for the ThreeFold ecosystem.
     You can find more on ThreeFold Connect [here](https://manual.threefold.io/#/3botconnect_install).

## Next, use the guided setup to create and configure your private VDC

- Both K8s and storage have their own flow – actions in order to deploy your own instance on top of the ThreeFold Grid.
- If you're feeling lost, each live tool has a tutorial on its page here on the wiki.

## Where to ask questions

- Feel free to ask us any questions you might have on [our forum](https://forum.threefold.io) in the feedback category.
- We also have a Telegram Group for TF Grid testers [here](https://t.me/joinchat/BwOvOxxgK59GmRoZ2_sM0w).

*Please keep in mind that eVDC is currently running on testnet. Mainnet is planned for early 2021.*

*Please forgive any instability you might encounter while our developers continue to work to bring you the best solutions possible and keep in mind the forum (linked directly above) is there for you to bring questions or report any issues.*
