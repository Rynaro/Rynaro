# Henrique A. Lavezzo · Rynaro

### I lead the guild, shape the systems, and still craft the tools.

I'm Henrique, an engineering leader born and living in Brazil. My craft is turning ambiguity into clear systems, helping teams move with confidence, and running experiments that **never claim more than the evidence allows**.

[Rynaro](https://github.com/Rynaro) comes from nowhere, and appears exactly where he is needed.

**Workbench:** [hlavezzo.me](https://hlavezzo.me) · **Front door:** [Eidolons](https://github.com/Rynaro/eidolons)

---

## Artifacts from the workbench

The newest work starts where ordinary tooling stops: agents that need a mythology, experiments that need a shape, and small companions made to keep the strange parts useful.

| Artifact | Transmutation |
|---|---|
| [**Eidolons**](https://github.com/Rynaro/eidolons) | A portable party of named specialists. Scout, plan, build, and check are separate crafts; a deterministic kernel assembles the party for the work at hand. |
| [**Magicite**](https://github.com/Rynaro/magicite) | Skills kept as inspectable engrams. Routes and audits them locally over MCP. It never executes them. |
| [**Ariramba**](https://github.com/Rynaro/ariramba) | Local agentic coding where every model action is a **proposal**, not permission. Confine, verify, leave the tree byte-clean. |
| [**Crystalium**](https://github.com/Rynaro/crystalium) | Shared memory for the party without making memory another agent. Four bounded layers, trust-aware writes, hybrid recall. |
| [**Lararium**](https://github.com/Rynaro/lararium) | A household companion for Claude Code. Warmth without obligation; growth that only moves forward. |
| [**Cardboard Box**](https://github.com/Rynaro/cardboard-box) | Distrobox made declarative. One Boxfile, a real TUI, and the craft of shipping outside the AI fog. |

---

## First circle (for newcomers to LLM coding)

One assistant should not have to scout, plan, build, debug, and document in the same breath. Start with a single scout, then grow the party.

```bash
curl -fsSL https://raw.githubusercontent.com/Rynaro/eidolons/main/cli/install.sh | bash
mkdir atelier-demo && cd atelier-demo
eidolons init --preset minimal --hosts claude-code --non-interactive --no-mcp
eidolons harness install
