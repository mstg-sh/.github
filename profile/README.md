<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mstg-sh/.github/main/profile/white.png">
  <img src="https://raw.githubusercontent.com/mstg-sh/.github/main/profile/black.png" width="120" alt="Mustang">
</picture>

### Agents on your machine.

### Nothing in the middle.

<sub>[`mstg.sh`](https://mstg.sh) · tools for people who let a coding agent loose on a real repo · no backend, no seats, no telemetry</sub>

</div>

---

A coding agent is a process running as you, with your git credentials, your AWS profile, and whatever `npx -y` pulled down this morning. Then it reads a README somebody else wrote and does what the README says. That is the whole security model. It is also the whole product, so nobody upstream is in a hurry to fix it.

The industry's answer is a dashboard. Ship every tool call to a SaaS, get a compliance PDF back, twelve dollars a seat. We looked at that for a while. The call is happening on this laptop. Decide here.

So we build the tools and ship them as files on your disk. The daemon listens on `127.0.0.1` and returns 403 to everything else. Receipts are JSONL. Snapshots are content-addressed. The lockfile is a lockfile. Read all of it with `cat`; delete the directory and we would never know.

Nothing personal. We just read your architecture diagram.

## House rules

**1. Runs on your machine.** Laptop, spare box, the Mac mini under the desk. Never our cloud. There is not one.

**2. Nothing in the middle.** No backend, no telemetry, no relay. If it left your disk, you sent it.

**3. Pay because you want to.** It works without paying. Paying keeps it alive. Nothing is held hostage.

Where a drop offers an account, it is one free GitHub sign-in that carries settings between your machines. Identity, not destination. Your work stays on your computer and everything keeps working if the account is gone.

## Drops

Every release is its own repo. Numbered, standalone, finished. Take the one you need.

| Drop | | |
| --- | --- | --- |
| `MSTG/003` | **[Mustang Firewall](https://github.com/mstg-sh/mustang-firewall)** · [mstg.sh/firewall](https://mstg.sh/firewall/) | `npx` is `curl \| sh` with a suit on. Pin every MCP server's tool surface, scan what the agent reads, hold `rm -rf /` for a click, rewind what a prompt did. Forty attacks in the redteam pack; run them against your own gate. |
| `MSTG/002` | **[Mustang Swarm](https://github.com/mstg-sh/mustang-swarm)** · [mstg.sh/swarm](https://mstg.sh/swarm/) | Give four agents the same task on the machines you already own. Each in its own worktree, each judged by your test suite. Keep the one that passes. |
| `MSTG/001` | **Security readiness** · in progress | Free SOC 2 configuration readiness for small technical teams. Point it at your GitHub, see what an auditor would. |

## What is missing?

Nominate a tool that should exist, or one that exists and should not phone home. Votes rank the list. We build from the top.

**[Nominate a tool](https://github.com/mstg-sh/.github/issues/new?template=target.yml)**

We're not saying it'll be yours. We're just saying the list is public.

---

<div align="center">
<sub>It is your computer. Use it.</sub>

<sub>**Your agents. Your machine.**</sub>
</div>
