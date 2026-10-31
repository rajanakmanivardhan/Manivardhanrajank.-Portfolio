# Rajanak Manivardhan — Glassmorphism Portfolio

Static portfolio for GitHub Pages. Built with plain HTML, CSS and JavaScript — no framework, package manager, build step or backend.

## Files

- `index.html` — complete website (markup, styles and scripts in one file)
- `assets/Manivardhan_Resume.pdf` — add your current PDF resume here before publishing

## Features

- Responsive glassmorphism layout
- Dark/light theme toggle (preference saved in browser local storage)
- Animated role text, scroll reveal and reading-progress indicator
- Project category filters
- Live public GitHub repository cards using the GitHub REST API (no token)
- Keyboard command palette (`Ctrl+K` / `⌘K`)
- Contact form that opens the visitor's email application using `mailto:`; it does not store or send data through a server
- Reduced-motion support and mobile navigation

## Before publishing

1. Check every personal detail, especially CGPA and contact links.
2. Put your latest resume PDF at `assets/Manivardhan_Resume.pdf`.
3. Add repository links to project cards only after those repositories are public.
4. Replace any project descriptions that do not exactly match the work you completed.
5. Open `index.html` locally and test the links and mobile layout.

## Deploy to GitHub Pages

Repository: `mani020405/mani020405.github.io`

### Upload through GitHub website

1. Open `https://github.com/mani020405/mani020405.github.io`.
2. Choose **Add file → Upload files**.
3. Upload `index.html` to the repository root.
4. Upload the `assets` folder containing `Manivardhan_Resume.pdf`.
5. Commit directly to `main` (or your configured publishing branch).
6. Open **Settings → Pages**.
7. Set **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
8. Wait for the Pages deployment to finish. Visit `https://mani020405.github.io`.

### Deploy from AlmaLinux / terminal

From the local clone of the repository:

```bash
cp /path/to/portfolio/index.html .
mkdir -p assets
cp /path/to/your/Manivardhan_Resume.pdf assets/Manivardhan_Resume.pdf

git status
git add index.html assets/Manivardhan_Resume.pdf
git commit -m "Build interactive glassmorphism portfolio"
git push origin main
```

If your publishing branch is not `main`, use that branch instead.

## Important notes

- GitHub Pages serves static files. This portfolio does not need a server.
- The GitHub API is public and unauthenticated here, so rate limits can apply. The page has a fallback state if the API is unavailable.
- The contact form uses the visitor's local email application. For a server-backed form, configure a trusted form provider or a small backend separately.
- Do not commit API keys, passwords, private SSH keys, or other secrets.
