# KordLoom

**Weaving complexity into things you can understand, control, and trust.**

KordLoom is an independent software company. Modern work arrives as a tangle: many
tools, many systems, many machines, many actors, records scattered across all of
them, and now AI doing real work alongside people. We weave those strands into
products that are simple to run, strong enough to rely on, and honest about what
they did.

Underneath every product runs the same warp. On a loom, the warp is the set of
threads stretched first, the ones every other thread crosses, and the fabric holds
because of them. KordLoom's warp is proof. Trust in a world of AI cannot rest on a
vendor's word, so where a KordLoom product acts, measures, or keeps a record, it can
show evidence anyone can verify.

Three products are public today. More are being built, and each one appears here
when it ships, not before.

## SwitchTender

One Go binary that runs Ansible, Terraform, OpenTofu, Bash, PowerShell, Python,
and Go across a fleet. Live host-by-task matrix, enforced approvals, and a
hash-chained audit you can verify offline. No Kubernetes, no Postgres, no Redis.
Migrate from AWX, Semaphore, Ascender, or Ansible Automation Platform in one
command. AI agents operate under the same gates and the same audit as human
operators.

- Site: [switchtender.com](https://switchtender.com)
- Code: [kordloom/switchtender](https://github.com/kordloom/switchtender)
- Install: [releases](https://github.com/kordloom/switchtender/releases) or `brew install kordloom/tap/switchtender`

## Whodar

Know who knows. An expertise locator for teams: find who to talk to about a
subject across Slack, GitHub, docs, and tickets, and see where the answer rests on
one person. Self-hosted, local by default, and it works with or without an LLM.

- Code: [kordloom/whodar](https://github.com/kordloom/whodar)

## LoomSeal

An open format for evidence someone else can check. One signed, chained,
anchored file, verified offline by a free Apache-2.0 tool with no account and
no server. Two independent implementations, cross-checked against shared
conformance vectors.

- Site: [loomseal.com](https://loomseal.com)
- Code: [kordloom/loomseal](https://github.com/kordloom/loomseal)
- Spec: [FORMAT.md](https://github.com/kordloom/loomseal/blob/main/FORMAT.md)
- CI: [loomseal-verify-action](https://github.com/kordloom/loomseal-verify-action)

SwitchTender and Whodar are fabric from this loom. LoomSeal is the warp beneath
them, and beneath what comes next.
