# 🐾 Bernese Mountain Dog — The Gentle Giant of the Alps

A beautiful, single-file tribute page dedicated to the magnificent Bernese Mountain Dog.
Built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no build tools required.

## ✨ Features

- **Stunning full-viewport hero** with animated floating paw prints and parallax-style design
- **Tri-color design palette** — inspired by the Berner's iconic black, white & rust coat
- **Live photo gallery** powered by the [Dog CEO API](https://dog.ceo/) with clickable lightbox
- **Scroll-reveal animations** via IntersectionObserver
- **Animated stat counters** and progress bars
- **Interactive flip cards** for fun facts
- **Full breed timeline** from 50 BCE to today
- **Custom cursor** with trailing animation (desktop)
- **Scroll progress indicator**
- **Fully responsive** — mobile, tablet, and desktop
- **Dark/light themed sections** for visual variety
- **Zero dependencies** — one `index.html` file

## 🚀 Deployment

### GitHub Pages
1. Push to `main` branch
2. Go to **Settings → Pages → Source: GitHub Actions**
3. The workflow in `.github/workflows/deploy.yml` handles the rest

### GitLab Pages
1. Push to `main` branch
2. `.gitlab-ci.yml` automatically builds and deploys

### Local Preview
Just open `index.html` in any browser — it works entirely offline except for the live photo gallery (which needs internet for the Dog CEO API).

## 🎨 Design Choices

| Element | Choice | Reason |
|---------|--------|--------|
| **Color Palette** | Black `#1A1208`, Rust `#B85C2C`, Gold `#D4A843`, Cream `#FAF6EE` | Mirrors the Berner's tri-color coat |
| **Heading Font** | Playfair Display | Elegant, classic — befitting a noble breed |
| **Body Font** | Inter | Clean, highly readable at all sizes |
| **Accent Font** | Dancing Script | Warm, handwritten feel for quotes |
| **Gallery Images** | Dog CEO API (live) + Wikimedia fallback | Real Berner photos, always fresh |

## 📋 Sections

1. **Hero** — Full-screen landing with animated paw prints
2. **Stats Bar** — Quick breed stats with animated counters
3. **About the Breed** — Introduction with featured photo
4. **History Timeline** — 2,000 years from Roman legions to today
5. **Temperament** — 6 personality trait cards with hover effects
6. **Coat & Appearance** — Color swatches, size charts, energy profiles
7. **Photo Gallery** — Live-loaded Berner photos with lightbox
8. **Health & Care** — Concerns and care tips
9. **Quote Banner** — Atmospheric full-width quote
10. **Fun Facts** — 3D flip cards revealing surprising stats
11. **Famous Berner Families** — Celebrity owners
12. **Is It Right for You?** — Honest yes/no ownership guide
13. **Footer** — Links and resources

## 📸 Image Credits

Gallery images are loaded dynamically from [Dog CEO](https://dog.ceo) — a free, open dog image API.
Fallback images from [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Bernese_Mountain_Dog) (CC licensed).

---

*Made with ❤️ for the most majestic dogs on earth.*
