# CKNE Preparation

A study checklist for Kubernetes networking preparation, organized by domain and competency. Use the checkboxes to track your progress through each topic.

## Domains and Competencies

The weights below reflect the preparation outline maintained in this repository.

| Domain | Weight |
| --- | --- |
| [Core Infrastructure and CNI](#core-infrastructure-and-cni) | 15% |
| [Service Networking and DNS](#service-networking-and-dns) | 25% |
| [Advanced Traffic Management](#advanced-traffic-management) | 20% |
| [Network Security and Policy](#network-security-and-policy) | 25% |
| [Observability](#observability) | 15% |
| **Total** | **100%** |

### Core Infrastructure and CNI

**Weight: 15%**

- [ ] Install and configure Container Network Interface (CNI) plugins.
- [ ] Manage IP address management (IPAM) and Pod CIDR allocation.
- [ ] Use Linux tools (`iptables`, `ip`, and `tcpdump`) to investigate packet-level issues.
- [ ] Troubleshoot Pod connectivity, including DNS and Pod-to-Pod communication.
- [ ] Configure multi-interface Pods.

### Service Networking and DNS

**Weight: 25%**

- [ ] Configure Layer 4 (L4) Services.
- [ ] Understand `kube-proxy` and CNI alternatives.
- [ ] Customize CoreDNS for Services.
- [ ] Troubleshoot Service network traffic.
- [ ] Configure Pod endpoint availability.
- [ ] Manage traffic with the Gateway API (`Gateway` and `HTTPRoute`).

### Advanced Traffic Management

**Weight: 20%**

- [ ] Optimize large language model (LLM) traffic.
- [ ] Implement routing to expose networks.
- [ ] Configure egress gateways for traffic leaving the cluster.
- [ ] Implement cross-cluster Service discovery and load balancing.

### Network Security and Policy

**Weight: 25%**

- [ ] Secure traffic with network policies.
- [ ] Implement node-level and Pod-level encryption.
- [ ] Manage TLS certificates for the Gateway API.
- [ ] Implement Pod-level authentication and authorization.

### Observability

**Weight: 15%**

- [ ] Analyze network health using metrics.
- [ ] Troubleshoot end-to-end network performance with tracing.
- [ ] Audit traffic with logs.
