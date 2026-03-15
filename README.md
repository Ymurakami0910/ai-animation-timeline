# What's Next? — AI in Animation

> A scenario-based timeline exploring how artificial intelligence will reshape storytelling, production pipelines, and creative jobs in the animation industry — from 2027 to 2036.

**Live site:** https://ymurakami0910.github.io/ai-animation-timeline/

---

## About

This is a university group assignment built for BCIT (2025). Instead of a traditional slide deck, we present our research as a horizontally scrolling, interactive timeline — inspired by editorial design and built entirely in a single HTML file.

The project explores three possible futures for AI in animation through the lens of an industry expert interview with **Justin Marmulk**, Production Coordinator at Netflix Animation.

---

## Team

| Name | Role |
|------|------|
| Jappan | Researcher |
| Tyler | Researcher |
| Yuri | Interview Coordinator · Website Development · Design |

---

## Structure

The timeline has **6 panels** that scroll horizontally:

| Panel | Content |
|-------|---------|
| 0 — Intro | Title screen |
| 1 — Team | Team member profiles |
| 2 — 2027 | Near-future scenario |
| 3 — 2031 | Mid-future scenario |
| 4 — 2036 | Far-future scenario |
| 5 — Closing | Final provocation |

Each year panel has **three scenarios** toggled via a button in the header:

- **Optimistic** — AI as a creative assistant; human storytelling leads
- **Most Likely** — AI-driven workflows become the industry standard
- **Pessimistic** — Automation hollows out technical roles; studios consolidate power

There is also a separate **Interview section** (accessible via the person icon in the header) featuring Justin Marmulk's bio, video clip slot, and pull quote.

---

## Expert Interview

**Justin Marmulk**  
Production Coordinator · Netflix Animation

Justin provided firsthand perspective on how AI tools are already being trialled in real studio pipelines — from pre-visualization to rendering automation — and shared his belief that audiences will ultimately prefer animation made with genuine human vision.

---

## Design

- **Style:** Cartoon Network × Apple Glassmorphism
- **Background:** Vivid multicolor gradient — always visible
- **Containers:** Frosted glass (`backdrop-filter: blur`)
- **Typography:** Barlow Condensed (headers) + Inter (body)
- **Accent color:** Deep orange `#ff5200`
- **Text:** Dark on glass — high contrast

---

## How to Edit

### Option 1 — Edit locally
1. Clone or download the repo
2. Open `index.html` in [VS Code](https://code.visualstudio.com/)
3. Install the **Live Server** extension for instant preview
4. Edit HTML/CSS directly — all content and styles are in one file

### Option 2 — Edit via GitHub + Claude
1. Make your edits locally and push to this repo
2. Share the raw file URL with Claude:
   ```
   https://raw.githubusercontent.com/ymurakami0910/ai-animation-timeline/main/index.html
   ```
3. Claude fetches the latest version, applies changes, returns the updated file
4. Upload the new file back to this repo — the live site updates automatically

---

## Adding Your Media

Three media slots are ready to be filled:

**Photos (team + Justin)**
```html
<!-- Replace the placeholder div with: -->
<img src="your-photo.jpg" alt="Name">
```

**Video interview embed (YouTube)**
```html
<!-- Replace the video slot placeholder with: -->
<iframe
  src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
  allowfullscreen>
</iframe>
```

**Media slots in timeline panels**
```html
<!-- Replace the <p> placeholder inside .media-slot with: -->
<img src="your-chart.png" alt="Description">
```

Upload image files directly to this repo, then reference them by filename.

---

## Sources

- [Cartoon Brew — Animation Jobs in the Age of AI: Luminate 2025 Report](https://www.cartoonbrew.com/tech/animation-jobs-in-the-age-of-ai-revelations-from-luminate-intelligences-2025-special-report-253718.html)
- [Smoking Chimney Studios — AI Transforming CGI Animation Workflows](https://smokingchimneystudios.com/ai-transforming-cgi-animation-workflows/)
- [Vitrina AI — AI in Film, Animation & Documentary 2024–2027](https://vitrina.ai/blog/ai-film-animation-documentary-2024-2027/)
- [SuperAGI — Future of Motion Graphics: AI in Animation & VFX 2025](https://web.superagi.com/future-of-motion-graphics-how-ai-is-revolutionizing-animation-and-visual-effects-in-2025/)
