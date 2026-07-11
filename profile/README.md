# 🖧 JaySync-Lab

> A personal homelab on **Proxmox VE** — DNS/ad-blocking, observability, home automation, a GPU-accelerated media stack, and a live in-browser terminal playground. Built and documented in the open.

[![Docs](https://img.shields.io/website?url=https%3A%2F%2Flab.anujajay.com&label=docs%20·%20lab.anujajay.com&up_message=online)](https://lab.anujajay.com)
[![Playground](https://img.shields.io/website?url=https%3A%2F%2Fjslnode.anujajay.com&label=playground%20·%20jslnode.anujajay.com&up_message=online)](https://jslnode.anujajay.com)

Everything runs on a single repurposed HP ProDesk under Proxmox VE, reachable anywhere through Tailscale, with every service, network decision, and change logged. Full docs live at **[lab.anujajay.com](https://lab.anujajay.com)**.

## 🔗 Repositories

| Repo | What it is | Live |
|:-----|:-----------|:-----|
| [**JaySync-Lab**](https://github.com/JaySync-Lab/JaySync-Lab) | Infrastructure docs + machine-readable inventory — the single source of truth | — |
| [**jaysync-lab-site**](https://github.com/JaySync-Lab/jaysync-lab-site) | The Next.js + Fumadocs site that publishes the docs | [lab.anujajay.com](https://lab.anujajay.com) |
| [**jaysync-lab-playground**](https://github.com/JaySync-Lab/jaysync-lab-playground) | Real, disposable Linux terminal sessions, spun up on demand | [jslnode.anujajay.com](https://jslnode.anujajay.com) |

## ⚡ Highlights

- **Documented properly** — infra is written down as MDX and auto-published; a push to the docs repo rebuilds the site with no manual steps.
- **Live terminal playground** — every visitor gets a genuine isolated container (cloned from a golden template, destroyed on disconnect), not a simulation. **Now live** at [jslnode.anujajay.com](https://jslnode.anujajay.com).
- **Built in the open** — five services across DNS, monitoring, smart home, media, and the playground, all traceable through changelogs and an implementation journal.
