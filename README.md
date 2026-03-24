# The Architect Edge — 10 AI Secrets Nobody Told You

An interactive blog + game teaching how AI actually works under the hood. Zero build step. Pure HTML/CSS/JS. Deploys to GitHub Pages in 2 minutes.

## 🎮 Features

- **10 detailed blog posts** — each reveals a hidden AI mechanic with named concepts, fixes, and takeaways
- **Interactive game** — 10 boss battles teaching the same concepts through gameplay
- **Mobile-first design** — works perfectly on phones and desktops
- **Dark theme** — cinematic design with coloured accents per chapter
- **Zero dependencies** — single HTML file, no build step, no npm, no React

## 📖 The 10 Secrets

| # | Title | What You Learn |
|---|-------|----------------|
| 🧠 | Context Window | Why AI forgets your instructions mid-chat |
| 👻 | Syntax Mirage | Why AI code looks perfect but breaks |
| 🌋 | Temperature | Why cranking temp up creates noise, not creativity |
| 🎭 | Confidence Trap | Why confident tone has zero link to accuracy |
| 🌱 | Few-Shot Power | Why 2 examples beat 500 words of instructions |
| ⚖️ | Order Bias | Why list position changes the AI's recommendation |
| 🔓 | System Prompts | Why your "secret" instructions can be extracted |
| 📚 | RAG Laziness | Why adding docs can make AI dumber |
| 🔒 | API vs Chat | Why API users get 10x better results |
| 🔮 | Probability | Why AI predicts words, not truth |

## 🚀 Deploy to GitHub Pages

### Option 1: Quick deploy (2 minutes)

1. Create a new GitHub repository named `thearchitectedge` (or any name)

2. Push the files:
```bash
cd thearchitectedge
git init
git add -A
git commit -m "Initial commit - The Architect Edge"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/thearchitectedge.git
git push -u origin main
```

3. Enable GitHub Pages:
   - Go to your repo → **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** → **/ (root)**
   - Click **Save**

4. Your site is live at: `https://YOUR_USERNAME.github.io/thearchitectedge/`

### Option 2: Using GitHub CLI

```bash
gh repo create thearchitectedge --public --source=. --remote=origin --push
# Then enable Pages in Settings → Pages → main branch
```

### Option 3: Custom domain

1. After enabling Pages, go to Settings → Pages → Custom domain
2. Enter your domain (e.g., `thearchitectedge.com`)
3. Add a CNAME record pointing to `YOUR_USERNAME.github.io`
4. Check "Enforce HTTPS"

## 📁 Project Structure

```
thearchitectedge/
├── index.html          # Everything - blog, game, styles, scripts
├── README.md           # This file
├── CNAME               # Custom domain (optional)
└── images/             # GIF assets (optional, for social sharing)
    ├── og-image.png    # Social share image
    └── favicon.ico     # Browser tab icon
```

## 🎨 Customisation

### Change brand name
Search and replace `THE ARCHITECT EDGE` and `@thearchitectedge` in `index.html`.

### Add your GIFs
The blog posts reference animated GIFs. Add them to `images/` and update the HTML.

### Add analytics
Add your Google Analytics or Plausible snippet before the closing `</head>` tag.

### Add social share image
Create a 1200x630 image and update the `og:image` meta tag in the `<head>`.

## 📱 Mobile Support

The site is fully responsive:
- Blog adapts to any screen width
- Game uses tap-friendly buttons (no keyboard needed)
- Navigation works via touch
- All text is readable on small screens

## 📊 Content Strategy

This site supports a weekly content pipeline:
1. Play the game to learn the concept
2. Read the detailed blog post for depth
3. Share the GIF + caption on Instagram/LinkedIn
4. Link back to the blog for full context

## License

Content and code by The Architect Edge. Free to use for personal learning.
Share with attribution: @thearchitectedge
