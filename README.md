# Owning Your AI Agent Systems

Slide deck, field guide, and first-week worksheet for Dan Schnurbusch's AI Era 2.0 talk. About twenty minutes, then questions. The audience is law firm owners.

Owning an agent system means owning the setup: skills, the tools you choose to connect, your data, and the approval rules. Hermes is a powerful open-source agent. Deploying its skills and connectors across a team took more technical work. A newer portal has improved that, and it is still more to run than a business admin console. The takeaway is that maintaining your own agent setup is now very easy with the admin controls in business-level accounts for ChatGPT, Claude, and Grok. Grok Bot is Dan's favorite right now because it is so easy to use. Grok Bot claims stay inside publicly documented features. The ChatGPT admin example is his firm's business account.

## Files

- `index.html`: the slide deck. One idea per slide. No build step and no external assets.
- `handout.html`: printable source for the six-page attendee PDF.
- `downloads/attendee-handout.pdf`: guide and first-week worksheet.
- `downloads/owning-agent-systems-offline.zip`: offline copy of the site, the PDF, and the demo packet.
- `SPEAKER-NOTES.md`: proposed pacing and talk track.
- `demo/RUNBOOK.md`: the live demo. `demo/sample-matters/` holds fictional matters only.

## Run

Open `index.html`, or serve this directory:

```bash
python3 -m http.server 4173 --bind 127.0.0.1
```

Open `index.html`. It is the deck.

Keys: Right, Down, Page Down, or Space advance. Left, Up, or Page Up go back. Home and End jump to the first or last slide. F toggles fullscreen.

The slides run without a network. The live demo needs a separate Grok Bot account and a network. The demo script is `demo/RUNBOOK.md`. The attendee handout is `handout.html` and the PDF, separate from the deck. Relative PDF links need this folder, not a lone copy of `index.html`. No analytics, external fonts, or client information are embedded. The browser remembers the last slide locally.

## PDF

Print `handout.html` from Chrome with backgrounds on and the CSS page size respected. The committed PDF was generated with headless Chrome, `printBackground: true`, `preferCSSPageSize: true`, and no header or footer. After a content change, confirm six content pages and no trailing blank page.

## Demo boundary

Use a Grok Bot account that has never held client information. Bots on one account share a computer. Do not run the demo on a firm account. The sample estates of June Calder and Arthur Pell are fictional.

## Content limits

Grok Bot behavior was checked against public docs in October 2026. Phone calls and Tailscale-style private-network access are described as coming. Lois, Vincent, Claude, and ChatGPT are named as the rest of the range, not scored. Ethics citations are discussion prompts. Confirm the rule text in your jurisdiction. Re-read vendor terms before a real matter is connected.

## Hosting

GitHub Pages, from the repository `main` branch, root directory. `.nojekyll` is present. There is no build. GitHub serves the site under its own terms. The page adds no analytics.
