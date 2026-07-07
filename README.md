# 🎨 Profile Studio

### 🚀 [**Open the live app →**](https://techwithgen.github.io/profile-studio/)

Fill in a short, friendly wizard and walk away with clean, ready-to-paste
Markdown — an animated header, tech badges, social links, live GitHub stats,
a contribution graph, and a dev quote.

---

## ✨ What you get

- **Animated header** — a customizable greeting + typing headlines
- **About section** — bio plus optional lines (currently learning, fun fact, pronouns…), drag to reorder
- **Tech stack** — 100+ technology badges across languages, frameworks, tools & more
- **Social links** — GitHub, LinkedIn, X, Instagram, TikTok, Pinterest, YouTube, email, and more
- **Live widgets** — GitHub stats, top languages, contribution graph, streak, and a random dev quote
- **14 accent colors** + light/dark themes + a custom color picker
- **Live preview** — see the rendered README and raw Markdown update as you type

## 📋 How to use

1. Open the [live app](https://techwithgen.github.io/profile-studio/).
2. Enter your GitHub username and fill in the steps.
3. Click **Download** (or **Copy**) to get your `README.md`.
4. Create a **public repo named exactly your username**, add the file it shows on your profile.

That's it. Nothing is uploaded, tracked, or stored on a server your work lives in your own browser.

## 🗂️ Project structure

```
index.html        Markup
css/styles.css    All styling
js/catalog.js     Tech + social data and badge helpers
js/app.js         Wizard logic, Markdown generation, live preview
```

No build step, no framework  open `index.html` locally, or host the folder on any static host.

## 🛠️ Run locally

Just open `index.html`. For a local server (optional):

```bash
npx serve .
# or
python3 -m http.server
```

## 🌐 Deploy (GitHub Pages)

1. Push this folder to a **public** repo.
2. **Settings → Pages → Deploy from a branch → main → / (root)**.
3. Live at `https://<username>.github.io/<repo>/`.

## ℹ️ About the live widgets

The stats, language, graph, streak, and quote cards are rendered by external
services (github-readme-stats, shields.io, readme-typing-svg, and others). They
load live wherever the README is shown and populate once a real GitHub username
is entered. If a widget's service is temporarily busy, the builder shows a small
"Renders on your live profile" placeholder — the card still appears on your
actual profile once its service recovers.

## 📄 License

MIT — free to use, share, and build on.
