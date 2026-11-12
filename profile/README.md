<div align="center">

<a href="https://github.com/SwaDeshiTech/prodhub">
  <img src="https://raw.githubusercontent.com/SwaDeshiTech/.github/main/assets/prodhub-pixel-icon.png" width="220" alt="ProdHub pixel-art deployment hub icon">
</a>

# SwaDeshiTech

### Build it once. Ship it anywhere. Operate it with confidence.

Developer-platform tools for teams building on Kubernetes.

[Explore the platform](https://github.com/SwaDeshiTech/prodhub) · [Use the CLI](https://github.com/SwaDeshiTech/prodhub-cli) · [Browse all repositories](https://github.com/orgs/SwaDeshiTech/repositories)

</div>

---

## The developer experience, end to end

From a pull request to a running workload, our projects aim to remove the sharp edges around application delivery. The focus is simple: give developers fast feedback and familiar tools, while giving platform teams reliable Kubernetes foundations.

```text
  code  ──►  build  ──►  deploy  ──►  discover  ──►  observe
               │            │             │
          CI Captain     ProdHub     Environment Orchestrator
               │            │             │
               └────────────┴─────────────┘
                         Kubernetes
```

## Start with the right project

| Project | What it does | Best for |
| --- | --- | --- |
| [**ProdHub**](https://github.com/SwaDeshiTech/prodhub) | Centralizes development and deployment workflows. | Platform-driven delivery |
| [**ProdHub CLI**](https://github.com/SwaDeshiTech/prodhub-cli) | Brings deployment, management, and monitoring to the terminal. | Developers who live in the shell |
| [**CI Captain**](https://github.com/SwaDeshiTech/ci-captain) | Connects Jenkins and GitHub Actions into one CI control plane. | Unified pipeline operations |
| [**Environment Orchestrator**](https://github.com/SwaDeshiTech/environment-orchestrator) | Provides namespace-local service discovery, DNS, and load balancing. | Ephemeral and Kubernetes-native environments |
| [**KubeSync**](https://github.com/SwaDeshiTech/kubesync) | Synchronizes ConfigMaps between Kubernetes namespaces. | Keeping environment configuration aligned |
| [**Base Helm Charts**](https://github.com/SwaDeshiTech/base-helm-charts) | Shared Helm building blocks for Kubernetes applications. | Repeatable application delivery |

## A platform that meets developers where they are

```bash
# Work from your terminal
git clone git@github.com:SwaDeshiTech/prodhub-cli.git
cd prodhub-cli
go build ./cmd/prodhub-cli

# Explore the wider platform
prodhub-cli --help
```

<details>
<summary><strong>What we care about</strong></summary>

<br>

- **Developer autonomy** — self-service workflows that do not hide the infrastructure.
- **Kubernetes-native operations** — tooling that works with the platform rather than around it.
- **Composable foundations** — focused services that can be adopted independently and integrated cleanly.
- **Operational clarity** — predictable environments, discoverable services, and observable delivery paths.

</details>

---

<div align="center">

**Shipping software should feel like creating—not coordinating.**

Explore [SwaDeshiTech on GitHub](https://github.com/SwaDeshiTech).

</div>
