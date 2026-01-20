# de-cluster-lab

## Overview
This organization manages a private mesh network via **Tailscale** to provide seamless and secure communication between distributed cluster nodes.

## Goals
- **Solve Network Isolation:** Bypass university/public Wi-Fi client isolation issues.
- **Fixed Infrastructure:** Use MagicDNS and fixed 100.x.y.z IPs to maintain cluster stability regardless of physical location.
- **High Performance:** Achieve low-latency, peer-to-peer (P2P) connections for data-intensive tasks like Kafka and Kubernetes.

## Getting Started
1. Log in to Tailscale using your GitHub account and select the `de-cluster-lab` organization.
2. Run `sudo tailscale up` on your machine.
3. Verify connectivity with `tailscale status`.
