# Rajanak Manivardhan — Cloud & Infrastructure Portfolio

A responsive, static portfolio built with plain HTML, CSS and JavaScript. It is designed for GitHub Pages and does not require Node.js, React, a package manager, a backend or API keys.

**Live site:** https://rajanakmanivardhan.github.io/Manivardhanrajank.-Portfolio/

## Project structure

```text
.
├── index.html
├── README.md
├── DEPLOYMENT.md
├── .nojekyll
└── assets/
    └── README.md
```

## What is included

- Hybrid visual system: professional content layout, selected glass panels and a terminal-style cloud summary.
- Responsive navigation, mobile menu, theme toggle and scroll progress.
- Cloud-focused positioning: AWS, Linux, networking and cloud support.
- Existing academic projects and current hands-on labs retained and clearly labelled.
- Project filters and GitHub public repository integration using the correct account.
- Accessible labels, keyboard-friendly native controls and reduced-motion support.
- Contact form that creates a `mailto:` draft. It does not send or store messages on a server.
- No fake skill percentages, invented certifications, unsupported job experience or fabricated project results.

## Personal details to verify before publishing

1. Confirm phone number `+91 9110508988` is the number you want publicly displayed.
2. Confirm the diploma CGPA from the official marks memo. It is intentionally omitted because earlier portfolio/resume records conflict.
3. Add the current resume PDF only after checking that it is the final version. This version does not show a broken resume-download button.
4. Add project repository links, screenshots and measurable outcomes only after those artifacts exist and are public.
5. Check all wording against the work you personally completed.

## Local preview

Open `index.html` directly in a browser, or run a local static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub integration

The repository cards call the unauthenticated public GitHub API for `rajanakmanivardhan`. GitHub may rate-limit unauthenticated requests. A fallback message and direct profile link remain available.

## Contact form limitation

The contact form uses `mailto:`. It opens the visitor's configured email application with a pre-filled message; it does not submit to a server, send mail automatically or retain form data. A real backend or form provider would need separate configuration.

## Deployment

See [DEPLOYMENT.md](DEPLOYMENT.md) for safe deployment instructions. No repository changes are made by generating this package.
