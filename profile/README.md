# JaySync-Lab

A personal homelab running on Proxmox VE — DNS/ad-blocking, observability,
home automation, and a GPU-accelerated media stack, all documented and
built out in the open. Full docs live at
[lab.anujajay.com](https://lab.anujajay.com).

**Repositories:**
- [JaySync-Lab](https://github.com/JaySync-Lab/JaySync-Lab) — the documentation and infrastructure wiki: every service, network decision, and change is logged here
- [jaysync-lab-site](https://github.com/JaySync-Lab/jaysync-lab-site) — the Next.js + Fumadocs site that publishes the docs above
- [jaysync-lab-playground](https://github.com/JaySync-Lab/jaysync-lab-playground) — an interactive terminal playground: real, disposable Linux sessions spun up on demand

The playground's session controller (Phase 3) is live — every session is a
fresh, isolated container, cloned and destroyed automatically. Phase 4
(the public-facing terminal interface) is in progress.
