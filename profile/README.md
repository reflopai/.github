<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../assets/03_lockup_horizontal.png">
    <img src="../assets/03_lockup_horizontal_dark.png" width="500" alt="reFLOP AI logo">
  </picture>
  
#
 
  **Making remote GPU computing feel local.**
 
  Building a developer-first, fault-tolerant distributed GPU compute network.
 
  [Website](https://reflopai.com) · [Open-source runtime](https://github.com/reflopai/reflop) · [Contact](https://reflopai.com/contact)
</div>

---
 
### Compute where you code.
 
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../assets/overview-dark.png">
    <img src="../assets/overview-light.png" width="840" alt="Your Python runs locally and unchanged. Only tensor operations travel to a GPU provider, where they run as validated operations in a sandboxed worker. The reFLOP AI control plane (in development) handles discovery, scheduling, auth and metering.">
  </picture>
</p>

Your code stays on your machine; only validated tensor operations reach the GPU. That's **[reFLOP](https://github.com/reflopai/reflop)**, our open-source runtime.
 
### What we're building
 
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../assets/building-dark.png">
    <img src="../assets/building-light.png" width="840" alt="Three stages. Remote tensor execution, available now: run PyTorch on a remote GPU from local Python. Managed compute, in development: capacity discovery, scheduling, authenticated sessions, metering and billing. Workload recovery, research and development: reassign workloads after provider failures and resume from independently persisted checkpoints.">
  </picture>
</p>
The longer-term goal is a network where developers request compute, not machines—while providers contribute capacity without exposing general-purpose shell access to strangers.
 
### Built on open source
 
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../assets/open-core-dark.png">
    <img src="../assets/open-core-light.png" width="840" alt="Two layers. The reFLOP AI managed platform (in development): orchestration, provider management, reliability services. It is built on the reFLOP open-source runtime (Apache-2.0, available): the reflop PyTorch client, the rootless reflopd daemon, an isolated worker, and a closed set of 582 operators.">
  </picture>
</p>

Explore the code, follow development, or contribute through the **[reFLOP repository](https://github.com/reflopai/reflop)**.
