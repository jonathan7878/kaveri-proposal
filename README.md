# Technical Hub × Kaveri University — Digital Presence Proposal

A static, single-page proposal site pitching Technical Hub's branding, digital marketing,
and T@G Portal services to Kaveri University. It opens with a connecting story — 10+ years
of experience, proven across Aditya University, Torii Minds, and the Nagarjuna Group of
Institutions — before walking through the full service offering and a dedicated T@G Portal
walkthrough.

## Tech stack
A static, responsive HTML/CSS/JS build:

- **HTML5** — semantic single-page layout
- **Bootstrap 5.3** (CDN) — responsive grid, navbar, carousels, utilities
- **Bootstrap Icons** (CDN)
- **Google Fonts** — Poppins (headings) + Open Sans (body)
- **Vanilla JavaScript** — scroll-reveal, animated stat counters, sticky-nav, back-to-top
- Embedded, privacy-enhanced YouTube videos for proof-of-work

No build step required — it's fully static.

## Structure
```
index.html     # all content sections
style.css      # theme (Technical Hub navy/orange + five service accents)
main.js        # interactivity
assets/        # logos, case-study creatives, and work-sample photos
```

## Sections
Hero · Stats · Proven Results (Aditya University, Torii Minds, Nagarjuna Group of
Institutions) · Video Work · Services · T@G Portal · Why Partner With Us · Benefits ·
CTA · Footer

## Run it
Open `index.html` directly in a browser, or serve the folder:
```powershell
python -m http.server 8743   # then visit http://localhost:8743
```
A `.claude/launch.json` is included so the site also previews automatically inside Claude Code.
