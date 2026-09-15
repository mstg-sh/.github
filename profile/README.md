<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mstg-sh/.github/main/profile/white.png">
  <img src="https://raw.githubusercontent.com/mstg-sh/.github/main/profile/black.png" width="120" alt="Mustang">
</picture>

### The agent runs on your laptop.

### So does everything else.

<sub>[`mstg.sh`](https://mstg.sh) · the load-bearing parts of running a coding agent · no server, no seats, no telemetry</sub>

</div>

---

A coding agent is a process running as your user. It has your SSH key, your npm token, your AWS profile and push access to main. It reads whatever is in the repo, including the README a stranger wrote, and it does what the text says. That is not a bug in one vendor's product. That is what a coding agent is.

You would not give a contractor that much access without a second pair of eyes and a way back. The agent should get both. Locally, in the same process tree, where a decision can actually stop the call instead of describing it afterwards.

So we build those parts and ship them as files on your disk. The gate listens on `127.0.0.1` and answers 403 to any other address. Receipts are newline-delimited JSON. Snapshots are content-addressed blobs. Open any of it with `cat`. Delete the directory and the software forgets everything; we never knew.

Nothing personal. We just read your architecture diagram.

## House rules

**1. Runs on your machine.** Laptop, spare box, the Mac mini under the desk. We do not have a cloud to sell you.

**2. Nothing in the middle.** No backend, no relay, no telemetry. If a byte left your disk, you sent it.

**3. Pay because you want to.** It works without paying. Paying keeps it going. Nothing is held for ransom.

Where a drop has an account, it is one free GitHub sign-in that carries settings between your machines. Identity, not destination. Your work stays on your computer, and everything keeps working if the account is gone.

## Drops

One repository, one name, one job. Install the one you need.

| Drop | | |
| --- | --- | --- |
| `MSTG/003` | **[Mustang Firewall](https://github.com/mstg-sh/mustang-firewall)** · [mstg.sh/firewall](https://mstg.sh/firewall/) | Most of your supply chain is one `npx -y` away. Hash every MCP server's tool surface and diff it on every start. Scan what the agent reads for instructions meant for the model. Hold `rm -rf /` for a click. Rewind what a prompt did. Forty attacks in the redteam pack; fire them at your own gate. |
| `MSTG/002` | **[Mustang Swarm](https://github.com/mstg-sh/mustang-swarm)** · [mstg.sh/swarm](https://mstg.sh/swarm/) | Same task, four agents, four worktrees, on hardware you already own. Your test suite picks the winner. "Done" is a claim; green is a result. |
| `MSTG/001` | **Security readiness** · in progress | Free SOC 2 configuration readiness for small technical teams. Point it at your GitHub and see what an auditor would. |

## What is missing?

Nominate a tool that should exist, or one that exists and should stop phoning home. Votes sort the list. We start at the top.

**[Nominate a tool](https://github.com/mstg-sh/.github/issues/new?template=target.yml)**

We're not saying it'll be yours. We're just saying the list is public.

---

<div align="center">
<sub>It is your computer. Use it.</sub>
</div>
