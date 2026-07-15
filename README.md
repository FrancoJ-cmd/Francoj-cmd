<div align="center">

```
███████╗██████╗  █████╗ ███╗   ██╗ ██████╗ ██████╗
██╔════╝██╔══██╗██╔══██╗████╗  ██║██╔════╝██╔═══██╗
█████╗  ██████╔╝███████║██╔██╗ ██║██║     ██║   ██║
██╔══╝  ██╔══██╗██╔══██║██║╚██╗██║██║     ██║   ██║
██║     ██║  ██║██║  ██║██║ ╚████║╚██████╗╚██████╔╝
╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝ ╚═════╝
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=9D4EDD&center=true&vCenter=true&width=600&lines=systems+%26+backend;distributed+systems%2C+built+from+scratch;4th-year+CS+%40+UNS;self-hosted%2C+start+to+finish" alt="Typing SVG" />

<a href="https://francoj.dev"><img src="https://img.shields.io/badge/francoj.dev-0D0A14?style=for-the-badge&logo=firefoxbrowser&logoColor=9D4EDD" alt="portfolio"/></a>
<a href="mailto:jarquefranco.1c@gmail.com"><img src="https://img.shields.io/badge/email-0D0A14?style=for-the-badge&logo=gmail&logoColor=9D4EDD" alt="email"/></a>

</div>

---

### `$ whoami`

Fourth-year Computer Science student at Universidad Nacional del Sur (Argentina), focused on systems programming: distributed systems, networking, and infrastructure. Currently open to remote internships and part-time roles.

Everything I use runs on my own hardware: the portfolio behind that badge is served from a Raspberry Pi through Caddy, WireGuard, and nftables. Self-hosting is the fastest way I know to learn how things actually work, and when something breaks at 3 AM, at least it's my fault.

---

### `$ cat tech_stack.yaml`

<div align="center">

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C](https://img.shields.io/badge/C-283593?style=for-the-badge&logo=c&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-B7410E?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)

</div>

---

### `$ ls -la ~/projects/`

```bash
drwxr-xr-x  godfs/              # distributed file system in Go, HDFS-inspired
drwxr-xr-x  hitlist/            # ranks Steam's most played games in real time
drwxr-xr-x  tfidf-summarizer/   # Rust NLP pipeline with a Python spaCy sidecar
drwxr-xr-x  ketobytes/          # bakery management CLI over SQLite
drwxr-xr-x  homelab/            # 10+ services on one Raspberry Pi, all self-hosted
lrwxrwxrwx  portfolio -> https://francoj.dev
```

| Project | What it is | Built with |
|---|---|---|
| [godfs](https://github.com/FrancoJ-cmd/godfs) | Fault-tolerant distributed file system: heartbeats, block replication, replica fallback. Stdlib only. | `Go` |
| [HitList](https://github.com/FrancoJ-cmd/HitList---Gaming-Hub) | Desktop app ranking Steam's top games live: player counts + review ratios, offline-first caching. | `Kotlin` `Compose` |
| [tfidf-summarizer](https://github.com/FrancoJ-cmd/tfidf-summarizer) | Extractive summarizer for Spanish text; Rust core talking JSON over pipes to a spaCy sidecar. | `Rust` `Python` |
| [ketobytes](https://github.com/FrancoJ-cmd/ketobytes) | Recipe-based bakery pricing: change one ingredient, everything repriced. | `Python` `SQLite` |

---

### `$ git log --author="Franco" --oneline`

```
* a3f8d19 fix: that thing that's been annoying me for weeks
* 9c2b7e4 refactor: because past me was an idiot
* 6d4f1a8 docs: explain what this does before I forget
* 2e8a5c3 chore: automate the thing I swore I'd only do once
* 7b1d9f6 feat: self-host another thing nobody asked for
* 4f6c2a1 test: break it on purpose to see what happens
* 8a3e7d2 wip: this worked in dev, let's see about prod
```

---

### `$ tail -f /var/log/current_status.log`

```log
[2026-07-14 15:47:32] INFO: Fighting with DNS. Again. Always DNS.
[2026-07-14 14:23:18] INFO: The distributed systems homework became a public repo. Worth it.
[2026-07-14 13:05:44] INFO: Deployed to the Pi. It worked first try. Suspicious.
[2026-07-14 11:42:07] DEBUG: Reading man pages like they're actual documentation
[2026-07-14 10:18:53] INFO: "This will only take 5 minutes" - started 3 hours ago
[2026-07-14 09:37:29] WARN: Edge case discovered. There are always more edge cases.
[2026-07-14 08:14:56] INFO: Coffee acquired. Proceed with debugging.
```

---

### `$ systemctl status franco.service`

```
● franco.service - Turning Coffee Into Distributed Systems
   Loaded: loaded (/etc/systemd/system/franco.service; enabled)
   Active: active (running) since 2023 (4th year of 5, UNS)
   Main PID: [REDACTED]
   Status: "open to remote internships / part-time roles"
   Tasks: 47 (46 are 'fix this later')
   Memory: mostly occupied by open browser tabs about obscure errors
   CGroup: /sys/fs/cgroup/users/franco
           └─ Last restart: 0d 6h 23m ago (that deployment went... okay)
```

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=FrancoJ-cmd&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0D0A14" height="165" alt="stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=FrancoJ-cmd&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0D0A14" height="165" alt="top languages"/>

<img src="https://raw.githubusercontent.com/FrancoJ-cmd/Francoj-cmd/output/github-contribution-grid-snake.svg" alt="contribution snake"/>

**Builds stuff. Breaks stuff. Fixes stuff. Repeats.**

```
Self-hosted because "the cloud" is just someone else's computer
```

<img src="https://komarev.com/ghpvc/?username=FrancoJ-cmd&color=9D4EDD&style=for-the-badge&label=PROFILE+VIEWS" alt="profile views"/>

</div>
