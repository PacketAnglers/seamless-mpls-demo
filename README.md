# Arista Seamless MPLS Demo

## QuickStart

From the terminal:

- Start the lab: `make start`
- Stop the lab: `make stop`
- Inspect the lab: `make inspect`

> [!TIP]
> For the best experience, the [VS Code ContainerLab Extension](https://containerlab.dev/manual/vsc-extension/) is Highly Recommended

## Overview

- 22 Nodes
- Built and validated with cEOS-Lab 4.35.0F

## Requirements

- [ContainerLab](https://containerlab.dev/install/) Host
- [cEOS-Lab image](https://www.arista.com/en/support/software-download)
- cEOS-Lab image imported into Docker as `ceos:latest`
- 32G RAM

## Topology

> [!NOTE]
> Physical Topology Overview

![Topology](./assets/images/topo.png)

## Control Plane - IGP Domains (ISIS-SR)

> [!NOTE]
> Intra-Domain LSPs

![Topology](./assets/images/igp-domains.png)

## Control Plane - BGP Labeled-Unicast

> [!NOTE]
> Inter-Domain LSPs

![Topology](./assets/images/lu.png)

## Control Plane - VPNv4

> [!NOTE]
> L3VPN Service

![Topology](./assets/images/vpnv4.png)
