<div align="center">

# Azeez Syed

**Software Engineer | Open Source Contributor**

19 merged PRs across 10 projects, including 3 CNCF graduated/incubating projects

[![Resume](https://img.shields.io/badge/Resume-View%20%26%20Download-2563EB?style=for-the-badge)](https://syedazeez337.github.io/resume/)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/azeez-alishah/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/syedazeez337)
[![Email](https://img.shields.io/badge/azeezalishah@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:azeezalishah@gmail.com)

</div>

---

## Open Source Contributions

### CoreDNS *(CNCF Graduated)* &mdash; 5 PRs

DNS server powering service discovery in Kubernetes.

| PR | Description |
|:---|:------------|
| [#7402](https://github.com/coredns/coredns/pull/7402) | Fix SRV record case handling per RFC 6763 |
| [#7413](https://github.com/coredns/coredns/pull/7413) | Fix TXT record comparison logic per RFC 1035 |
| [#7438](https://github.com/coredns/coredns/pull/7438) | Deflake multisocket restart tests |
| [#7798](https://github.com/coredns/coredns/pull/7798) | Harden ready/pprof/health plugins against slowloris (gosec G114) |
| [#7799](https://github.com/coredns/coredns/pull/7799) | Fix integer overflow warnings across 26 files (gosec G115) |

### Cilium *(CNCF Graduated)* &mdash; 3 PRs

eBPF-based networking, security, and observability for Kubernetes.

| PR | Description |
|:---|:------------|
| [#38874](https://github.com/cilium/cilium/pull/38874) | Fix Gateway API reconciler crash when TLSRoute CRD is absent |
| [#39275](https://github.com/cilium/cilium/pull/39275) | Fix parentRef matching to validate Group and Kind |
| [#40272](https://github.com/cilium/cilium/pull/40272) | Add egressDeny policy docs, backported to v1.16-v1.18 |

### Strimzi *(CNCF Incubating)* &mdash; 2 PRs

Kafka on Kubernetes via operators and custom resources.

| PR | Description |
|:---|:------------|
| [#12277](https://github.com/strimzi/strimzi-kafka-operator/pull/12277) | Separate MirrorMaker 2 metrics from Kafka Connect defaults |
| [#12281](https://github.com/strimzi/strimzi-kafka-operator/pull/12281) | Add KafkaNodePool resource counter metric |

### Kamaji &mdash; 2 PRs

Kubernetes control plane manager for multi-tenant clusters.

| PR | Description |
|:---|:------------|
| [#1043](https://github.com/clastix/kamaji/pull/1043) | Add unique controller names to fix Prometheus metric conflicts |
| [#1044](https://github.com/clastix/kamaji/pull/1044) | Remove k8s.io/apiserver dep that broke workqueue metrics |

### Kagent &mdash; 2 PRs

Kubernetes-native AI agent platform.

| PR | Description |
|:---|:------------|
| [#1178](https://github.com/kagent-dev/kagent/pull/1178) | Fix agent deletion ID format mismatch |
| [#1195](https://github.com/kagent-dev/kagent/pull/1195) | Fix Helm chart for custom release names |

### Additional Contributions

| Project | PR | Description |
|:--------|:---|:------------|
| [Aqua Trivy](https://github.com/aquasecurity/trivy-checks) | [#514](https://github.com/aquasecurity/trivy-checks/pull/514) | Refine RBAC check to flag only critical verbs |
| [Sourcemeta Core](https://github.com/sourcemeta/core) | [#2040](https://github.com/sourcemeta/core/pull/2040) | Replace hash map with bitset for O(1) vocabulary lookups |
| [Fluvio](https://github.com/fluvio-community/fluvio) | [#4626](https://github.com/fluvio-community/fluvio/pull/4626) | Fix duplicate field in Topic CRD breaking ArgoCD |
| [Yardstick](https://github.com/StacklokLabs/yardstick) | [#55](https://github.com/StacklokLabs/yardstick/pull/55) | Use MCP\_TRANSPORT env var for ToolHive compat |
| [go-exhaustruct](https://github.com/GaijinEntertainment/go-exhaustruct) | [#117](https://github.com/GaijinEntertainment/go-exhaustruct/pull/117) | Add bug report issue template |

---

## Projects

<table>
<tr>
<td>

### [Purple AI Sandbox](https://github.com/syedazeez337/purple-ai-sandbox)

Secure runtime for untrusted AI agents with multi-layer defense: eBPF packet filtering, syscall validation, and resource enforcement.

`Rust` `eBPF` `Seccomp BPF` `Tokio` `Axum`

</td>
<td>

### [BTE](https://github.com/syedazeez337/bte)

Deterministic behavioral testing engine for CLI/TUI applications. Spawns real processes in a PTY, verifies behavior via YAML test specs.

`Rust`

</td>
</tr>
</table>

---

## Skills

```
Languages:     Go, C++
Cloud Native:  Kubernetes, Cilium, CoreDNS, Gateway API, Helm, DNS Protocol
Observability: Prometheus, Kafka/Strimzi, Grafana
Systems:       Linux, Networking (TCP/IP, DNS), Git, GitHub Actions, Docker
```
