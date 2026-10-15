# Amir Fauzan — Interactive Portfolio

Premium static HTML/CSS/JavaScript portfolio, made from Amir Fauzan's resume and source materials. No build process, frontend framework, server, database or API key is required.

## Quick start

1. Extract this directory.
2. Double-click `index.html` to open it in a modern browser.
3. For reliable local media behavior and testing, serve the folder using `python -m http.server 8000`, then open `http://localhost:8000`.
4. To host publicly, publish the folder as a static site with GitHub Pages, Netlify, or Vercel.

## What works

- Responsive navigation and active-section tracking
- Recruiter Mode toggle, persisted in localStorage when permitted
- Interactive keyboard-driven portfolio terminal (type `help`)
- Four project case studies (real facts; clear solo/group status)
- HALALCHAIN 8-step interactive illustrative simulation and sample sensor incident
- Clickable conceptual enterprise topology and illustrative link failover
- Category-switched skill explorer
- Actual narrated HALALCHAIN slide presentation with local video playback
- Original HTML demos, linked locally
- Authentic selected images from the URIIS presentation (source deck also included)
- Resume download, GitHub and LinkedIn links, clipboard email, mailto contact form

## Accuracy and limitations

HALALCHAIN is a TRL 3 **functional laboratory prototype** (not a commercial deployment or halal certifier). Hardware-integrated RFID/ESP32 work is confirmed by Amir. Some original project evidence is available, but no HALALCHAIN GitHub repository was supplied. Its demo and network topology are explicitly labeled as illustrations. Original GNS3 diagrams and screenshots of DH Motorsport / Asrah FC weren't provided, so these showcase visuals are intentionally marked conceptual/illustrative. Awards are user-confirmed. The original presentation is a narrated slide video, not proof footage of a live physical scan.

The two external full-stack GitHub repo URLs are transcribed from the supplied resume; validate public accessibility before publishing. Confirm that you are permitted to publish the source video and presentation slides.

The header hero uses the portrait image embedded in Amir's supplied CV. Its modest original image resolution limits sharpness on large displays; replacing it with a higher-quality photo will improve visual quality.

## Content and assets

- `index.html`: semantic page markup and static copy
- `assets/style.css`: layout, responsive behavior and design system
- `assets/app.js`: interactions, case-study records, demos and terminal commands
- `assets/img/amir-portrait.jpg`: portrait extracted from original resume
- `assets/img/halalchain-*.webp`: images rendered from actual URIIS presentation slides
- `assets/media/halalchain-presentation.mp4`: optimized local copy of the submitted presentation video
- `assets/media/HALALCHAIN-URIIS-2026.pdf`: source presentation
- `assets/media/amir-fauzan-resume.pdf`: source resume
- `demos/*-original.html`: original submitted interactive HTML demos
- `MASTER_PROMPT.md`: copy/paste master prompt for redesign, extension and future updates

## Next edits

1. Add authentic screenshots from DH Motorsport and Asrah FC and replace the illustrated mockups.
2. Add real GNS3 topology screenshots and specific configuration/testing evidence.
3. Add HALALCHAIN RFID demo footage and authentic URIIS exhibition/award photos when available.
4. Verify all award titles, credential details and privacy choices before making the site public.
5. Optionally add your verified personal LinkedIn photo, selected certifications/badges, and newer project evidence.

## Privacy

The page publicly displays an email address and approximate home location (Kuala Selangor), but omits the personal phone number supplied on the resume. The downloadable resume includes the phone number, so review it before public deployment.

## Accessibility notes

The portfolio supports keyboard navigation, accessible dialog labels, Escape to dismiss overlays, reduced-motion preferences, clear status labels, and responsive layout. The inline 3D-like visual treatments are CSS/SVG rather than a heavy rendering engine. Additional manual accessibility and browser testing is recommended before production deployment.
