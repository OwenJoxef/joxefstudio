# Joxef Studio

Website for **Owen Joxef** — DJ gigs, studio practice, and beginner lessons in Södermalm / Skanstull, Stockholm.

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 5173
```

Then visit `http://localhost:5173`.

## Contact form

The enquiry form uses [FormSubmit](https://formsubmit.co) and sends to `Dondjbookings@gmail.com`.

The **first** submission triggers a confirmation email from FormSubmit — open that email and confirm once. After that, enquiries arrive normally.

## Photos

Drop images into `assets/` with these exact names and they appear automatically (until then, a placeholder is shown):

| File | Where it shows |
| --- | --- |
| `hero.jpg` | Hero, right side (shown in black and white) |
| `club-loop.mp4` + `club-loop.jpg` | DJ bookings section: silent looping clip (4:5) and its still frame |
| `studio.jpg` | Studio section, full setup (16:9) |
| `portrait.jpg` | About section (847 × 928, shown at up to 360px wide) |

## Publish (GitHub Pages)

When your GitHub account is ready:

1. Create a repo (e.g. `joxefstudio`)
2. Push this project
3. Enable **Settings → Pages → Deploy from branch** (`main` / root)
4. Point **joxefstudio.se** DNS to GitHub Pages when the domain is registered
