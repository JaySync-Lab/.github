# 🖧 JaySync-Lab

> A personal homelab on **Proxmox VE** — DNS/ad-blocking, observability, home automation, a GPU-accelerated media stack, and a live in-browser terminal playground. Built and documented in the open.

[![Docs](https://img.shields.io/website?url=https%3A%2F%2Fjaysynclab.com&label=docs%20·%20jaysynclab.com&up_message=online)](https://jaysynclab.com)
[![Playground](https://img.shields.io/website?url=https%3A%2F%2Fjslnode.jaysynclab.com&label=playground%20·%20jslnode.jaysynclab.com&up_message=online)](https://jslnode.jaysynclab.com)

Everything runs on a single repurposed HP ProDesk under Proxmox VE, reachable anywhere through Tailscale, with every service, network decision, and change logged. Full docs live at **[jaysynclab.com](https://jaysynclab.com)**.

## 🔗 Repositories

| Repo | What it is | Live |
|:-----|:-----------|:-----|
| [**JaySync-Lab**](https://github.com/JaySync-Lab/JaySync-Lab) | Infrastructure docs + machine-readable inventory — the single source of truth | — |
| [**jaysync-lab-site**](https://github.com/JaySync-Lab/jaysync-lab-site) | The Next.js + Fumadocs site that publishes the docs | [jaysynclab.com](https://jaysynclab.com) |
| [**jaysync-lab-playground**](https://github.com/JaySync-Lab/jaysync-lab-playground) | Real, disposable Linux terminal sessions, spun up on demand | [jslnode.jaysynclab.com](https://jslnode.jaysynclab.com) |

## ⚡ Highlights

- **Documented properly** — infra is written down as MDX and auto-published; a push to the docs repo rebuilds the site with no manual steps.
- **Live terminal playground** — every visitor gets a genuine isolated container (cloned from a golden template, destroyed on disconnect), not a simulation. **Now live** at [jslnode.jaysynclab.com](https://jslnode.jaysynclab.com).
- **Built in the open** — five services across DNS, monitoring, smart home, media, and the playground, all traceable through changelogs and an implementation journal.
