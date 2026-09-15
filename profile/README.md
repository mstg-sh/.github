<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mstg-sh/.github/main/profile/white.png">
  <img src="https://raw.githubusercontent.com/mstg-sh/.github/main/profile/black.png" width="120" alt="Mustang">
</picture>

### Agents on your machine.

### Nothing in the middle.

<sub>[`mstg.sh`](https://mstg.sh) · local-first tooling for AI coding agents · no backend, no seats, no telemetry</sub>

</div>

---

A coding agent is a process on your machine with your keys, your git push and your files. Everything built around it sits somewhere else. The control plane is a dashboard. The safety layer is a relay. The audit trail is a seat licence. Your code goes up so a chart can come down.

That is backwards. The thing that watches an agent should sit next to the agent. The thing that runs four of them should be your CPU. There is no server in the middle unless somebody wanted one there.

So we build the tools ourselves and release them. No backend. The only network calls are the ones your agent's provider already makes. Runs, receipts, snapshots, lockfiles: files on your disk, in formats you can read with `cat`.

Nothing personal. We just read your architecture diagram.

## House rules

**1. Runs on your machine.** Your laptop, your spare box, your rack. Never our cloud.

**2. Nothing in the middle.** No backend, no telemetry, no relay. Files on disk you can read.

**3. Pay because you want to.** The useful product works without payment. Supporting Mustang keeps it alive. It is not the price of getting your files back.

Where a drop offers an account, it is one free account, signed in with GitHub, that carries your settings between your machines. It is an identity, not a destination: your work stays on your computer, and everything keeps working if the account is gone.

## Drops

Every release is its own repo. Numbered, standalone, finished.

| Drop | | |
| --- | --- | --- |
| `MSTG/003` | **[Mustang Firewall](https://github.com/mstg-sh/mustang-firewall)** · [mstg.sh/firewall](https://mstg.sh/firewall/) | Pin, scan, redteam and rewind your coding agent. A gate on every tool call, on your laptop, with a receipt. |
| `MSTG/002` | **[Mustang Swarm](https://github.com/mstg-sh/mustang-swarm)** · [mstg.sh/swarm](https://mstg.sh/swarm/) | Run coding agents on the machines you already own. Several agents, one task, isolated worktrees, your tests decide. |
| `MSTG/001` | **Security readiness** · in progress | Free SOC 2 configuration readiness for small technical teams. |

## What is the agent era missing?

Submissions are open. People nominate a tool that should exist, or one that exists but phones home. We rank by votes and build the one at the top.

**[Nominate a tool](https://github.com/mstg-sh/.github/issues/new?template=target.yml)**

We're not saying it'll be yours. We're just saying the list is public.

---

<div align="center">
<sub>It is your computer. Use it.</sub>

<sub>**Your agents. Your machine.**</sub>
</div>
