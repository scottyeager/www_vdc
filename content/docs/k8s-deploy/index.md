---
description: ''
sidebar: 'docs'
prev: '/docs/start-upgrade/'
next: '/docs/k8s-upload/'
---

# Deploy K8s Cluster

## First, visit the [ThreeFold VDC Marketplace](https://vdc-mkt.threefold.io)

- This deployment creates the K3S Lightweight Kubernetes implementation in Zero-OS
- K3S is full conformant production-ready Kuberrnetes distribution with the following changes:   
   - It is packaged as a single binary
   - It adds support to sqlite3 as default storage. Etcd3, MySQL and Postgres are also supported
   - It wraps Kubernetes and other components in a single, simple launcher
   - It is secure by default with reasonable defa&ults for lightweight environments
   -  It eliminates the need to expose a port on Kubernetes worker nodes fopr the kubelet API by exposing this API to the Kubernetes control plane nodes over a websockert tunnel. 
   
   More info can be found [here](https://github.com/rancher/k3s)
   
   
   - You'll need to log in through 3Bot Connect, an authenticator for the ThreeFold Now ecosystem.
- You can find more on ThreeFold Connect [here](https://manual.threefold.io/#/3botconnect_install).

## Next, use the guided setup to create your private VDC

- Both K8S and S3 storage have their own flow – actions in order to deploy your own instance on top of the ThreeFold Grid.
- If you're feeling lost, each live tool has a tutorial on its page here on the wiki.

## Where to ask questions

- Feel free to ask us any questions you might have on [our forum](https://forum.threefold.io) in the feedback category.
- We also have a Telegram Group for TF Grid testers [here](https://t.me/joinchat/BwOvOxxgK59GmRoZ2_sM0w).

*Please keep in mind that ThreeFold Now is currently running on testnet. Some of the first solutions will be coming to mainnet in December.*

*Please forgive any instability you might encounter while our developers continue to work to bring you the best solutions possible and keep in mind the forum (linked directly above) is there for you to bring questions or report any issues.*

*As we are operating in demo mode, your deployments will be automatically be cancelled after three hours once you have had a chance to see what is possible.*

