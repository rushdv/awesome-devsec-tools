# 🛠️ Dev & Security Toolkit

> A categorized collection of essential tools for **web developers** and **cybersecurity professionals** — from building to breaking (ethically).

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📖 Table of Contents

- [🔴 Cybersecurity Tools](#-cybersecurity-tools)
  - [Reconnaissance](#reconnaissance)
  - [Scanning & Enumeration](#scanning--enumeration)
  - [Exploitation](#exploitation)
  - [Password Attacks](#password-attacks)
  - [Web Application Hacking](#web-application-hacking)
  - [Network Analysis](#network-analysis)
  - [Forensics & Analysis](#forensics--analysis)
  - [Reverse Engineering](#reverse-engineering)
  - [OSINT](#osint)
  - [CTF Tools](#ctf-tools)
- [🔵 Web Development Tools](#-web-development-tools)
  - [Frontend Frameworks](#frontend-frameworks)
  - [Backend Frameworks](#backend-frameworks)
  - [Databases](#databases)
  - [Dev Environment & CLI](#dev-environment--cli)
  - [Testing](#testing)
  - [Deployment & DevOps](#deployment--devops)
  - [AI & Code Assistants](#ai--code-assistants)
  - [Design & UI](#design--ui)
  - [Package Managers & Build Tools](#package-managers--build-tools)
- [🟢 General Developer Tools](#-general-developer-tools)
  - [Version Control](#version-control)
  - [API Development](#api-development)
  - [Documentation](#documentation)
  - [Productivity](#productivity)

---

## 🔴 Cybersecurity Tools

### Reconnaissance

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **Nmap** | [nmap.org](https://nmap.org) | Network discovery and security auditing tool | Linux/Win/Mac |
| **Shodan** | [shodan.io](https://www.shodan.io) | Search engine for internet-connected devices | Web |
| **theHarvester** | [GitHub](https://github.com/laramies/theHarvester) | Email, subdomain, and open port reconnaissance | Python |
| **Maltego** | [maltego.com](https://www.maltego.com) | Visual link analysis for OSINT and recon | Linux/Win/Mac |
| **Recon-ng** | [GitHub](https://github.com/lanmaster53/recon-ng) | Full-featured web reconnaissance framework | Python |
| **Amass** | [GitHub](https://github.com/owasp-amass/amass) | In-depth attack surface mapping and asset discovery | Go |
| **DNSRecon** | [GitHub](https://github.com/darkoperator/dnsrecon) | DNS enumeration script | Python |

### Scanning & Enumeration

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **Nessus** | [tenable.com](https://www.tenable.com/products/nessus) | Professional vulnerability scanner | Linux/Win/Mac |
| **OpenVAS** | [openvas.org](https://www.openvas.org) | Open-source vulnerability scanning framework | Linux |
| **Nikto** | [GitHub](https://github.com/sullo/nikto) | Web server scanner for dangerous files/programs | Perl |
| **Gobuster** | [GitHub](https://github.com/OJ/gobuster) | Directory/file & DNS busting tool | Go |
| **ffuf** | [GitHub](https://github.com/ffuf/ffuf) | Fast web fuzzer for content discovery | Go |
| **enum4linux** | [GitHub](https://github.com/CiscoCXSecurity/enum4linux) | Tool for enumerating info from Windows/Samba | Bash |
| **Wapiti** | [wapiti3.ovh](https://wapiti3.ovh) | Web application vulnerability scanner | Python |

### Exploitation

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **Metasploit** | [metasploit.com](https://www.metasploit.com) | World's most used penetration testing framework | Linux/Win/Mac |
| **SQLmap** | [sqlmap.org](http://sqlmap.org) | Automatic SQL injection and takeover tool | Python |
| **BeEF** | [beefproject.com](https://beefproject.com) | Browser exploitation framework | Ruby |
| **ExploitDB** | [exploit-db.com](https://www.exploit-db.com) | Archive of public exploits and vulnerable software | Web |
| **Searchsploit** | [GitHub](https://github.com/offensive-security/exploitdb) | Offline copy of ExploitDB for local search | Bash |

### Password Attacks

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **Hashcat** | [hashcat.net](https://hashcat.net) | World's fastest password recovery utility | Linux/Win/Mac |
| **John the Ripper** | [openwall.com](https://www.openwall.com/john/) | Password security auditing and recovery tool | Linux/Win/Mac |
| **Hydra** | [GitHub](https://github.com/vanhauser-thc/thc-hydra) | Fast network login cracker (FTP, SSH, HTTP, etc.) | Linux |
| **Medusa** | [foofus.net](http://foofus.net/goons/jmk/medusa/medusa.html) | Speedy parallel network login auditor | Linux |
| **CeWL** | [GitHub](https://github.com/digininja/CeWL) | Custom wordlist generator from websites | Ruby |
| **SecLists** | [GitHub](https://github.com/danielmiessler/SecLists) | Collection of wordlists for security assessments | All |

### Web Application Hacking

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **Burp Suite** | [portswigger.net](https://portswigger.net/burp) | Web security testing platform | Linux/Win/Mac |
| **OWASP ZAP** | [zaproxy.org](https://www.zaproxy.org) | Free web application security scanner | Linux/Win/Mac |
| **XSSer** | [GitHub](https://github.com/epsylon/xsser) | Automated XSS detection and exploitation framework | Python |
| **wfuzz** | [GitHub](https://github.com/xmendez/wfuzz) | Web fuzzer for parameters, directories, auth | Python |
| **Commix** | [GitHub](https://github.com/commixproject/commix) | Command injection exploitation tool | Python |
| **DirBuster** | [OWASP](https://owasp.org/www-project-dirbuster/) | Multi-threaded directory/file brute forcer | Java |

### Network Analysis

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **Wireshark** | [wireshark.org](https://www.wireshark.org) | World's most popular network protocol analyzer | Linux/Win/Mac |
| **tcpdump** | [tcpdump.org](https://www.tcpdump.org) | Command-line packet analyzer | Linux/Mac |
| **Ettercap** | [ettercap-project.org](https://www.ettercap-project.org) | Man-in-the-middle attacks on LAN | Linux/Win/Mac |
| **Bettercap** | [bettercap.org](https://www.bettercap.org) | Swiss army knife for network attacks and monitoring | Go |
| **Scapy** | [scapy.net](https://scapy.net) | Packet manipulation library and tool | Python |
| **Netcat** | [netcat.sourceforge.net](http://netcat.sourceforge.net) | Networking utility — "Swiss army knife of TCP/IP" | Linux/Win/Mac |
| **hping3** | [hping.org](http://www.hping.org) | TCP/IP packet assembler/analyzer | Linux |

### Forensics & Analysis

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **Autopsy** | [autopsy.com](https://www.autopsy.com) | Digital forensics platform and GUI for Sleuth Kit | Linux/Win |
| **Volatility** | [volatilityfoundation.org](https://www.volatilityfoundation.org) | Memory forensics framework | Python |
| **Binwalk** | [GitHub](https://github.com/ReFirmLabs/binwalk) | Firmware analysis and extraction tool | Python |
| **Foremost** | [foremost.sourceforge.net](http://foremost.sourceforge.net) | File recovery based on headers/footers | Linux |
| **strings** | Built-in | Extract human-readable text from binary files | Linux/Mac |
| **ExifTool** | [exiftool.org](https://exiftool.org) | Read/write metadata in images, audio, and video | Perl |

### Reverse Engineering

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **Ghidra** | [ghidra-sre.org](https://ghidra-sre.org) | NSA's free reverse engineering framework | Linux/Win/Mac |
| **IDA Free** | [hex-rays.com](https://hex-rays.com/ida-free/) | Industry-standard interactive disassembler | Linux/Win/Mac |
| **radare2** | [rada.re](https://rada.re) | Open-source reverse engineering framework | Linux/Win/Mac |
| **x64dbg** | [x64dbg.com](https://x64dbg.com) | Open-source Windows debugger | Windows |
| **GDB** | [gnu.org](https://www.gnu.org/software/gdb/) | GNU project debugger | Linux/Mac |
| **pwndbg** | [GitHub](https://github.com/pwndbg/pwndbg) | GDB plug-in for exploit development | Python |

### OSINT

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **Sherlock** | [GitHub](https://github.com/sherlock-project/sherlock) | Find usernames across social networks | Python |
| **SpiderFoot** | [spiderfoot.net](https://www.spiderfoot.net) | Automated OSINT collection and visualization | Python |
| **Whois** | [whois.net](https://www.whois.net) | Domain registration information lookup | Web/CLI |
| **Censys** | [censys.io](https://censys.io) | Internet-wide scanner and search engine | Web |
| **Hunter.io** | [hunter.io](https://hunter.io) | Find and verify email addresses | Web |
| **IntelX** | [intelx.io](https://intelx.io) | Intelligence X search engine for leaked data | Web |

### CTF Tools

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **pwntools** | [GitHub](https://github.com/Gallopsled/pwntools) | CTF framework and exploit development library | Python |
| **CyberChef** | [GitHub](https://github.com/gchq/CyberChef) | Web app for encoding, decoding, analysis & more | Web |
| **RsaCtfTool** | [GitHub](https://github.com/RsaCtfTool/RsaCtfTool) | RSA attacks for CTF competitions | Python |
| **StegSolve** | [GitHub](https://github.com/zardus/ctf-tools/tree/master/stegsolve) | Steganography analysis tool | Java |
| **zsteg** | [GitHub](https://github.com/zed-0xff/zsteg) | Detect hidden data in PNG/BMP files | Ruby |
| **GTFOBins** | [gtfobins.github.io](https://gtfobins.github.io) | Curated list of Unix binaries for privilege escalation | Web |

---

## 🔵 Web Development Tools

### Frontend Frameworks

| Tool | Source | Description | Language |
|------|--------|-------------|----------|
| **React** | [react.dev](https://react.dev) | Component-based UI library by Meta | JavaScript |
| **Next.js** | [nextjs.org](https://nextjs.org) | Full-stack React framework with SSR/SSG | JavaScript/TS |
| **Vue.js** | [vuejs.org](https://vuejs.org) | Progressive JavaScript framework | JavaScript |
| **Svelte** | [svelte.dev](https://svelte.dev) | Compiler-based UI framework with no virtual DOM | JavaScript |
| **Astro** | [astro.build](https://astro.build) | Static site builder optimized for content sites | JavaScript |
| **Angular** | [angular.io](https://angular.io) | Platform for building mobile and desktop apps | TypeScript |

### Backend Frameworks

| Tool | Source | Description | Language |
|------|--------|-------------|----------|
| **Node.js** | [nodejs.org](https://nodejs.org) | JavaScript runtime for server-side development | JavaScript |
| **Express.js** | [expressjs.com](https://expressjs.com) | Minimal and flexible Node.js web framework | JavaScript |
| **Fastify** | [fastify.dev](https://fastify.dev) | Fast and low overhead web framework for Node.js | JavaScript |
| **Django** | [djangoproject.com](https://www.djangoproject.com) | High-level Python web framework | Python |
| **FastAPI** | [fastapi.tiangolo.com](https://fastapi.tiangolo.com) | Modern, fast API framework for Python | Python |
| **Laravel** | [laravel.com](https://laravel.com) | PHP framework for elegant web applications | PHP |
| **Spring Boot** | [spring.io](https://spring.io/projects/spring-boot) | Java framework for production-ready apps | Java |
| **Hono** | [hono.dev](https://hono.dev) | Ultrafast web framework for edge environments | TypeScript |

### Databases

| Tool | Source | Description | Type |
|------|--------|-------------|------|
| **PostgreSQL** | [postgresql.org](https://www.postgresql.org) | Advanced open-source relational database | SQL |
| **MySQL** | [mysql.com](https://www.mysql.com) | World's most popular open-source database | SQL |
| **MongoDB** | [mongodb.com](https://www.mongodb.com) | Document-oriented NoSQL database | NoSQL |
| **Redis** | [redis.io](https://redis.io) | In-memory data structure store and cache | NoSQL |
| **SQLite** | [sqlite.org](https://www.sqlite.org) | Lightweight embedded SQL database | SQL |
| **Prisma** | [prisma.io](https://www.prisma.io) | Next-generation ORM for Node.js & TypeScript | ORM |
| **Drizzle ORM** | [orm.drizzle.team](https://orm.drizzle.team) | TypeScript ORM with SQL-like syntax | ORM |
| **Supabase** | [supabase.com](https://supabase.com) | Open-source Firebase alternative with PostgreSQL | BaaS |
| **Firebase** | [firebase.google.com](https://firebase.google.com) | Google's app development platform | BaaS |
| **PlanetScale** | [planetscale.com](https://planetscale.com) | MySQL-compatible serverless database | SQL |

### Dev Environment & CLI

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **VS Code** | [code.visualstudio.com](https://code.visualstudio.com) | Most popular code editor | Linux/Win/Mac |
| **Neovim** | [neovim.io](https://neovim.io) | Hyperextensible Vim-based text editor | Linux/Win/Mac |
| **Warp** | [warp.dev](https://warp.dev) | AI-powered modern terminal | Mac/Linux |
| **tmux** | [GitHub](https://github.com/tmux/tmux) | Terminal multiplexer for session management | Linux/Mac |
| **zsh + Oh My Zsh** | [ohmyz.sh](https://ohmyz.sh) | Feature-rich shell framework | Linux/Mac |
| **Starship** | [starship.rs](https://starship.rs) | Minimal, fast cross-shell prompt | Linux/Win/Mac |
| **Docker** | [docker.com](https://www.docker.com) | Platform for containerizing applications | Linux/Win/Mac |

### Testing

| Tool | Source | Description | Language |
|------|--------|-------------|----------|
| **Jest** | [jestjs.io](https://jestjs.io) | JavaScript testing framework | JavaScript |
| **Vitest** | [vitest.dev](https://vitest.dev) | Vite-native unit test framework | JavaScript |
| **Playwright** | [playwright.dev](https://playwright.dev) | End-to-end browser testing | JavaScript |
| **Cypress** | [cypress.io](https://www.cypress.io) | Front-end testing tool | JavaScript |
| **pytest** | [pytest.org](https://pytest.org) | Simple and powerful Python testing framework | Python |
| **Postman** | [postman.com](https://www.postman.com) | API development and testing platform | App |

### Deployment & DevOps

| Tool | Source | Description | Type |
|------|--------|-------------|------|
| **Vercel** | [vercel.com](https://vercel.com) | Platform for frontend frameworks and static sites | Cloud |
| **Netlify** | [netlify.com](https://www.netlify.com) | All-in-one platform for web projects | Cloud |
| **Railway** | [railway.app](https://railway.app) | Simple cloud platform for full-stack apps | Cloud |
| **Render** | [render.com](https://render.com) | Unified cloud to build and run all your apps | Cloud |
| **GitHub Actions** | [GitHub](https://github.com/features/actions) | CI/CD automation directly in GitHub | CI/CD |
| **Nginx** | [nginx.org](https://nginx.org) | High-performance web server and reverse proxy | Server |
| **Caddy** | [caddyserver.com](https://caddyserver.com) | Modern web server with automatic HTTPS | Server |
| **Coolify** | [coolify.io](https://coolify.io) | Self-hosted Heroku/Netlify alternative | Self-hosted |

### AI & Code Assistants

| Tool | Source | Description | Type |
|------|--------|-------------|------|
| **Claude** | [claude.ai](https://claude.ai) | Anthropic's AI assistant for coding & analysis | AI |
| **GitHub Copilot** | [github.com/copilot](https://github.com/features/copilot) | AI pair programmer in VS Code and more | AI |
| **Cursor** | [cursor.com](https://cursor.com) | AI-first code editor built on VS Code | Editor |
| **Windsurf** | [codeium.com/windsurf](https://codeium.com/windsurf) | AI-powered IDE by Codeium | Editor |
| **Claude Code** | [claude.ai/code](https://claude.ai/code) | Agentic CLI coding assistant by Anthropic | CLI |
| **v0** | [v0.dev](https://v0.dev) | Vercel's AI for generating UI components | AI |
| **Pieces** | [pieces.app](https://pieces.app) | AI-powered developer productivity tool | App |

### Design & UI

| Tool | Source | Description | Type |
|------|--------|-------------|------|
| **Tailwind CSS** | [tailwindcss.com](https://tailwindcss.com) | Utility-first CSS framework | CSS |
| **shadcn/ui** | [ui.shadcn.com](https://ui.shadcn.com) | Reusable components built with Radix + Tailwind | Components |
| **Radix UI** | [radix-ui.com](https://www.radix-ui.com) | Unstyled, accessible UI component primitives | Components |
| **Figma** | [figma.com](https://www.figma.com) | Collaborative design and prototyping tool | App |
| **Framer Motion** | [framer.com/motion](https://www.framer.com/motion/) | Production-ready animation library for React | JavaScript |
| **GSAP** | [gsap.com](https://gsap.com) | Professional-grade JavaScript animation | JavaScript |
| **Lucide Icons** | [lucide.dev](https://lucide.dev) | Beautiful and consistent open-source icon set | SVG |
| **Aceternity UI** | [ui.aceternity.com](https://ui.aceternity.com) | Trending animated UI components | Components |

### Package Managers & Build Tools

| Tool | Source | Description | Language |
|------|--------|-------------|----------|
| **npm** | [npmjs.com](https://www.npmjs.com) | Node package manager (default with Node.js) | JavaScript |
| **pnpm** | [pnpm.io](https://pnpm.io) | Fast, disk-efficient package manager | JavaScript |
| **Bun** | [bun.sh](https://bun.sh) | All-in-one JS runtime + package manager + bundler | JavaScript |
| **Vite** | [vitejs.dev](https://vitejs.dev) | Next-generation frontend build tool | JavaScript |
| **Turbopack** | [turbo.build](https://turbo.build/pack) | Incremental bundler optimized for JavaScript | JavaScript |
| **esbuild** | [esbuild.github.io](https://esbuild.github.io) | Extremely fast JavaScript bundler | Go |

---

## 🟢 General Developer Tools

### Version Control

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **Git** | [git-scm.com](https://git-scm.com) | Distributed version control system | Linux/Win/Mac |
| **GitHub** | [github.com](https://github.com) | Code hosting with collaboration features | Web |
| **GitLab** | [gitlab.com](https://gitlab.com) | DevOps platform with built-in CI/CD | Web |
| **Lazygit** | [GitHub](https://github.com/jesseduffield/lazygit) | Simple terminal UI for git commands | Go |
| **Git LFS** | [git-lfs.com](https://git-lfs.com) | Large file storage extension for Git | All |

### API Development

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **Postman** | [postman.com](https://www.postman.com) | API platform for building and using APIs | App/Web |
| **Insomnia** | [insomnia.rest](https://insomnia.rest) | Open-source API client and design tool | App |
| **Bruno** | [usebruno.com](https://www.usebruno.com) | Fast and git-friendly open-source API client | App |
| **Hoppscotch** | [hoppscotch.io](https://hoppscotch.io) | Open-source API development ecosystem | Web/App |
| **Thunder Client** | [VS Code](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client) | Lightweight API client inside VS Code | Extension |

### Documentation

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **Docusaurus** | [docusaurus.io](https://docusaurus.io) | Build optimized websites quickly with React | JavaScript |
| **GitBook** | [gitbook.com](https://www.gitbook.com) | Document everything from teams to APIs | Web |
| **Notion** | [notion.so](https://www.notion.so) | All-in-one wiki, docs, and project management | Web/App |
| **Obsidian** | [obsidian.md](https://obsidian.md) | Markdown-based personal knowledge base | App |
| **readme.so** | [readme.so](https://readme.so) | Online README editor with drag-and-drop sections | Web |

### Productivity

| Tool | Source | Description | Platform |
|------|--------|-------------|----------|
| **GitHub CLI** | [cli.github.com](https://cli.github.com) | GitHub in your terminal | Linux/Win/Mac |
| **tldr** | [tldr.sh](https://tldr.sh) | Simplified community man pages | CLI |
| **fzf** | [GitHub](https://github.com/junegunn/fzf) | General-purpose command-line fuzzy finder | Linux/Mac |
| **bat** | [GitHub](https://github.com/sharkdp/bat) | `cat` clone with syntax highlighting | Linux/Win/Mac |
| **ripgrep** | [GitHub](https://github.com/BurntSushi/ripgrep) | Extremely fast text search tool | Linux/Win/Mac |
| **httpie** | [httpie.io](https://httpie.io) | Modern, user-friendly HTTP client for CLI | Python |
| **curlie** | [GitHub](https://github.com/rs/curlie) | The power of curl with the ease of httpie | Go |

---

## 🎓 Learning Resources

### Cybersecurity
- [TryHackMe](https://tryhackme.com) — Learn cybersecurity through hands-on labs
- [HackTheBox](https://www.hackthebox.com) — Elite platform to practice penetration testing
- [PortSwigger Web Academy](https://portswigger.net/web-security) — Free web security training by Burp Suite makers
- [OWASP Top 10](https://owasp.org/www-project-top-ten/) — Top 10 web application security risks
- [PentesterLab](https://pentesterlab.com) — Learn web penetration testing and code review

### Web Development
- [The Odin Project](https://www.theodinproject.com) — Free full-stack curriculum
- [Full Stack Open](https://fullstackopen.com) — Free deep dive into modern web development
- [javascript.info](https://javascript.info) — Modern JavaScript tutorial
- [web.dev](https://web.dev) — Google's guidance for modern web development
- [roadmap.sh](https://roadmap.sh) — Developer roadmaps for any stack

---

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

1. Fork the repository
2. Add your tool under the correct category
3. Follow the existing table format
4. Submit a pull request with a clear description

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/rushdv">rushdv</a></sub>
</div>