# Owning Your Agent Systems

First-draft presentation and attendee field guide for Dan Schnurbusch's 30-minute AI Era 2.0 talk.

## Files

- `index.html`: self-contained presentation plus readable guide, inline SVG and no external assets.
- `handout.html`: printable source for the six-page attendee PDF.
- `downloads/attendee-handout.pdf`: guide, first-job worksheet, and official source links.
- `downloads/owning-agent-systems-offline.zip`: offline site package.
- `SPEAKER-NOTES.md`: proposed pacing and talk track.

## Run

Double-click `index.html`, or serve this directory with `python3 -m http.server 4173 --bind 127.0.0.1`.

Presentation mode: `index.html?mode=present#s1`.

Keys: Right/Space/PageDown advance one reveal or scene. Left/PageUp go back. Home/End select the first/last scene. G switches guide/presentation. F enters/exits fullscreen. Tab retains standard focus behavior.

The guide and full presentation run without a network. Relative PDF links require the downloaded package, not just a standalone copy of `index.html`. Product-resource links require internet. No analytics, external fonts, or client information are embedded. Browser local storage remembers the last scene; worksheet text is not transmitted.

## PDF regeneration

Use Chrome headless printing of `handout.html` with print backgrounds enabled and CSS page size respected. The committed PDF was generated with Chrome's CDP `Page.printToPDF` API, `printBackground: true`, `preferCSSPageSize: true`, `displayHeaderFooter: false`. Verify six content pages and no footer-only overflow page after changes.

## Content limits

All matter examples are fictional. The continuum is an architectural decision map, not a scored product comparison. Verify current product/plan capabilities and terms before procurement. Presenter timing is a proposed plan, not rehearsal evidence.

## Hosting

Designed for GitHub Pages from the repository's `main` branch, root directory. No build dependencies or server required. GitHub provides hosting logs under its terms; the page itself adds no analytics.
