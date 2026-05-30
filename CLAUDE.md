# Claude context — WEBCAM / Lindt LiveCam

## Memory
At the start of each session, read the memory files from:
https://github.com/Ikatrefon/claude-memory

Key files:
- `user_profile.md` — who Michał is, collaboration style
- `infrastructure.md` — VPS, Docker, nginx, deployment process
- `feedback_lindt_font.md` — always use Marcellus font in Lindt projects
- `project_webcam.md` — LiveCam widget architecture, YouTube IDs, layout editor

## Quick facts
- Font in all Lindt projects: **Marcellus** (Google Fonts)
- Live URL: https://lds-lindt-webcam.mdmresearch.com
- VPS: 195.35.56.37, SSH: `ssh -i ~/.ssh/id_ed25519 root@195.35.56.37`
- YouTube embeds require HTTP server (not file://), use: `python3 -m http.server 8090`
- Layout editor: press **L** in browser, "Kopiuj CSS" → console.log
