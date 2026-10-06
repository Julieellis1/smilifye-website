# Smilifye — Dental Clinic Website

A complete, responsive multi-page website for a modern dental clinic — rebuilt from scratch with original copy and AI-generated imagery, inspired by the structure and art direction of the Smilifye Webflow template.

## Pages

| Page | File |
|---|---|
| Home | `index.html` |
| About Us | `about.html` |
| Services | `services.html` |
| Service Details | `service-details.html` |
| Our Doctors | `doctors.html` |
| Doctor Details | `doctor-details.html` |
| Blog | `blogs.html` |
| Blog Details | `blog-details.html` |
| Contact / Book Appointment | `contact.html` |

## Features

- **Design system** — deep-teal palette (`#011f23`, `#022f34`), cream footer, pale-mint sections, Sora typography (Google Fonts), pill buttons with rotating arrow badges
- **Shared components** — sticky header with Pages mega-dropdown, mobile slide-in nav, dark-teal CTA banner, FAQ accordion + call card, footer
- **Interactions** (vanilla JS, no dependencies) — blur-fade scroll reveals, animated count-up stats, story & testimonial carousels, Why-Choose-Us tabs, appointment form with confirmation state
- **Fully responsive** — desktop, tablet, and mobile layouts
- **Original content** — all copy written fresh; all photography AI-generated for this build

## Run locally

No build step needed — it's plain HTML/CSS/JS. Serve the folder with any static server:

```bash
cd smilifye-website
python3 -m http.server 8000
# open http://localhost:8000
```

Or just open `index.html` directly in a browser (Google Fonts requires an internet connection).

## Structure

```
smilifye-website/
├── index.html
├── about.html
├── services.html
├── service-details.html
├── doctors.html
├── doctor-details.html
├── blogs.html
├── blog-details.html
├── contact.html
└── assets/
    ├── css/
    │   └── style.css      # entire design system
    ├── js/
    │   └── main.js        # nav, carousels, tabs, accordion, counters, reveals
    └── img/               # 21 AI-generated webp images
```

## Notes

- This is an original re-implementation for learning/portfolio purposes — not affiliated with the Webflow template author.
- The appointment form is front-end only (shows a confirmation message); wire it to a backend or form service for production use.
