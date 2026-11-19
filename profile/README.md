<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../assets/reflop-mark-light.png">
    <img src="../assets/reflop-mark-dark.png" width="172" alt="reFLOP AI logo">
  </picture>

  # reFLOP AI

  **Making remote GPU computing feel local.**

  Building a developer-first, fault-tolerant distributed GPU compute network.

  [Website](https://reflopai.com) · [Open-source runtime](https://github.com/reflopai/reflop) · [Contact](https://reflopai.com/contact)
</div>

---

### Compute where you code.

reFLOP AI is building infrastructure that connects machine learning developers with remote GPU capacity—without requiring them to move their entire development environment to another machine.

Our foundation is **[reFLOP](https://github.com/reflopai/reflop)**, an open-source runtime for executing supported PyTorch tensor operations on remote GPUs. Instead of giving users a remote shell or running arbitrary customer programs on the GPU provider's machine, reFLOP uses a constrained operator interface.

### What we're building

| | |
| --- | --- |
| **Remote tensor execution** | Offload supported PyTorch computations to remote GPU workers while retaining a local Python development workflow. |
| **Managed compute** *— in development* | Discover GPU capacity, schedule workloads, establish authenticated sessions, and handle metering and billing. |
| **Workload recovery** *— research & development* | Reassign supported workloads after provider failures and recover from independently persisted checkpoints. |

The longer-term goal is a network where developers request compute, not machines—while providers contribute capacity without exposing general-purpose shell access to strangers.

### Built on open source

**reFLOP** is available under the **Apache License 2.0**. The runtime and the planned managed platform are distinct: the open-source project handles the constrained execution path; reFLOP AI is building orchestration, provider management, and reliability services around it.

Explore the code, follow development, or contribute through the [reFLOP repository](https://github.com/reflopai/reflop).

<sub>**Development status:** The open-source runtime exists today. The managed GPU network, usage-based billing, and automated checkpoint-based failover described above are planned capabilities, not currently offered as production services. The constrained execution model limits what customers can run on provider machines; it does not, by itself, guarantee confidentiality of customer tensor data from providers.</sub>
