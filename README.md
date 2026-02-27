# LinuxPlain 🟢

> Linux explained in plain English. With a terminal to practice in.

**Live demo:** [nombuilds.github.io/LinuxPlain](https://nombuilds.github.io/LinuxPlain/)

---

## What is this?

LinuxPlain is a free, open-source Linux learning app built as a single HTML file.

Every command is explained in plain English, backed by a real-world analogy, and practised in a simulated terminal — right next to the lesson. No signup. No ads. No login. Just open it and learn.

Built for people who have never touched a terminal. Ends with a full guided walkthrough of OverTheWire Bandit, the most popular Linux security challenge in the world.

---

## Why I built it

Any Linux learning resource i used either:
- Dumps a wall of text with no way to practice
- Throws you into a real terminal with no explanation
- Requires a signup, subscription, or a VM spinning up for 60 seconds

I was studying for my Google IT Support certificate and learning OverTheWire Bandit. I couldn't find anything that explained commands in plain English AND let me practice immediately in the same place. So I Vibe-coded it.

---

## Features

- **68 commands** across 5 tiers — from `pwd` to Docker
- **Plain English + real-world analogy** for every single command
- **Simulated terminal** built in — no setup, no VM, no waiting
- **Tab completion** — press Tab to complete commands and filenames
- **Command history** — press Up arrow to recall previous commands
- **Mobile quick-key bar** — `/` `|` `-` `*` and more, one tap on mobile
- **Live file explorer** — see your filesystem update as you type commands
- **Pipe support** — `ls | grep`, `sort | uniq -u`, `cat | wc -l` all work
- **Progress tracking** — saved to localStorage, no account needed
- **OverTheWire Bandit walkthrough** — all 34 levels explained plainly
- **Command reference** — searchable, filterable, always available
- **Zero dependencies** — one HTML file, works offline after first load

---

## The 5 Tiers

| Tier | Name | Commands | Time |
|------|------|----------|------|
| 1 | Absolute Beginner | pwd, ls, cd, mkdir, touch, cat, cp, mv, rm, clear, man, echo | ~45 min |
| 2 | Intermediate | grep, find, pipes, redirects, sort, uniq, wc, head, tail, chmod, sudo + more | ~75 min |
| 3 | Advanced | strings, base64, tr, xxd, gzip, tar, diff, awk, sed, xargs, cut, ps, kill + more | ~90 min |
| 4 | DevOps Real World | ssh, netcat, openssl, nmap, systemctl, journalctl, git, docker + more | ~90 min |
| 5 | OverTheWire Bandit | All 34 Bandit levels with plain English methodology | ~3 hrs |

---

## Screenshots

*Coming soon*

---

## How to use

**Option 1 — Just open it**

Download `index.html` and open it in any browser. That's it. No server needed.

**Option 2 — GitHub Pages**

Fork this repo, enable GitHub Pages on the `main` branch, and it's live instantly.

**Option 3 — Clone and run locally**

```bash
git clone https://github.com/nombuilds/LinuxPlain.git
cd LinuxPlain
open index.html
```

---

## Tech stack

- Pure HTML, CSS, and JavaScript — zero frameworks, zero dependencies
- `FakeFS` class — a simulated Linux filesystem that lives in memory
- `localStorage` — progress tracking without any backend
- Google Fonts (Fira Code, Inter) — loaded via CDN
- Single file — everything in `index.html`

---


## OverTheWire Bandit

LinuxPlain includes a guided walkthrough of all 34 Bandit levels. This is not a solutions page — it's a methodology guide. Each level explains:

- What the challenge is teaching
- Which commands to use and why
- The real-world analogy for what's happening

No actual passwords are shown. This is an unofficial educational guide only.

> *LinuxPlain is not affiliated with OverTheWire. All challenge content belongs to OverTheWire.*

---

## Roadmap

- [ ] Android app via Capacitor
- [ ] Claude API integration — "explain this differently" button
- [ ] Cloud sync via Supabase (optional, account-free stays default)
- [ ] More Bandit-style challenges built into the simulator
- [ ] `ls -R` recursive directory listing
- [ ] FakeFS persistence across sessions

---

## Contributing

This is a single HTML file. To contribute:

1. Fork the repo
2. Edit `index.html`
3. Test in a browser
4. Open a pull request with a clear description of what you changed and why

Please do not add external libraries or frameworks. The zero-dependency single-file approach is intentional.

---

## License

MIT — free to use, fork, and modify. If you build something with it, a mention would be appreciated but is not required.

---

## Author

Built by [@nombuilds](https://github.com/nombuilds) — an IT support student who got tired of learning Linux the hard way.

*If this helped you, consider starring the repo. It helps other beginners find it.*
