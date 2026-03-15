The official website for **Legally Bonding**, a podcast covering everything law — landmark cases, solo deep dives into legal topics, and candid conversations with legal professionals.

🌐 **Live site:** [yourusername.github.io/legally-bonding](https://yourusername.github.io/legally-bonding) 

---

## About the Podcast

Legally Bonding makes the law accessible, compelling, and real. Whether it's a landmark Supreme Court ruling, the fine print in a contract, or a criminal trial that gripped the nation — every episode breaks it down in plain English, with context, nuance, and zero condescension.

New episodes drop bi- weekly — solo deep dive, guest conversations with barristers, solicitors, judges, and legal academics, and everything in between.

---

## What's on the Site

- 🎙 **Episodes** — Links to all episodes with descriptions and platform badges (Spotify, Apple Podcasts, YouTube)
- ✍️ **Blog** — Hot topic! Written takes on legal news, explainers, and opinions
- 👤 **About** — The story behind the podcast
- 📚 **Reading List** — Growing list of Books to ensure you continue to think critically about these issues 
- 📬 **Newsletter** — Sign-up for episode alerts, legal news and info on the latest hot topic 

---

## Built With

- Plain HTML, CSS, and JavaScript — no frameworks, no dependencies
- Hosted for free via [GitHub Pages](https://pages.github.com/)
- Fonts from [Google Fonts](https://fonts.google.com/) (Playfair Display + DM Sans)

---

## How to Edit the Site

All content lives in one file: `index.html`

**Option 1 — Edit on GitHub directly**
1. Open `index.html` in your repo
2. Click the pencil ✏️ icon
3. Use Ctrl+F to find the text you want to change
4. Edit and click **Commit changes** — the site updates automatically

**Option 2 — Edit locally**
1. Clone the repo: `git clone https://github.com/yourusername/legally-bonding.git`
2. Open `index.html` in VS Code or any text editor
3. Make your changes and save
4. Push to GitHub: `git add . && git commit -m "your update" && git push`

---

## Deploying to GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Set source to the `main` branch, `/ (root)` folder
3. Click **Save**
4. Your site will be live at `https://yourusername.github.io/legally-bonding`

> Changes you push to the `main` branch go live within 1–2 minutes automatically.

---

## Adding New Episodes

Find this section in `index.html` and copy an existing episode card, updating the episode number, title, description, tags, and duration:

```html
<div class="episode-card fade-in">
  <div class="ep-card-num">EP. 043 · MAR 17, 2026</div>
  <div class="ep-card-title">Your Episode Title Here</div>
  <div class="ep-card-desc">Your episode description here.</div>
  <div class="ep-card-tags"><span class="tag">Topic</span></div>
  <div class="ep-card-footer">
    <span class="ep-duration">🎙 45 min</span>
    <a href="YOUR_EPISODE_LINK" class="ep-listen-btn">▶ Listen</a>
  </div>
</div>
```

---

## License

© 2026 Legally Bonding. All rights reserved.
