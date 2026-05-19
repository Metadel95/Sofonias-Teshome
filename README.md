# Sofonias Teshome — Real Estate Agent Website

Personal one-page portfolio website for **Sofonias Teshome**, Sales Agent at [Metro Real Estate™](https://www.metrorealestateet.com), Addis Ababa, Ethiopia.

---

## 🚀 Deploy to Vercel (2 minutes)

### Option A — Vercel Dashboard (Recommended)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **New Project**
3. Import your GitHub repo
4. Vercel auto-detects it as a static site — just click **Deploy**
5. Done! You'll get a live URL like `sofonias-teshome.vercel.app`

### Option B — Vercel CLI
```bash
npm i -g vercel
vercel
```

---

## 📁 Project Structure

```
sofonias-website/
├── index.html      # Complete one-page site (HTML + CSS + JS)
└── README.md       # This file
```

No build step required. Pure HTML/CSS/JS — zero dependencies.

---

## ✏️ How to Customize

### Update Contact Info
In `index.html`, search for these and replace:
- `+251913554296` — Sofonias's personal WhatsApp/phone
- `+251938060606` — Metro office line
- `sales@metrorealestateet.com` — Metro office email

### Add a Real Photo
1. Add a photo file (e.g. `photo.jpg`) to the project
2. In `index.html`, find the `.agent-portrait` section
3. Replace the initials circle with:
```html
<img src="photo.jpg" alt="Sofonias Teshome" style="width:100%;height:100%;object-fit:cover;" />
```

### Update Stats
Find the `.about-stats` section and update the numbers (clients served, properties sold, etc.)

### Gallery
The gallery tries to load images from Metro Real Estate's website. If they block hotlinking, the placeholders will show instead. To use your own photos, add image files and change the `src` attributes in the `.gallery-grid` section.

---

## 🎨 Design

- **Aesthetic**: Dark luxury with gold accents — matching Metro Real Estate's brand
- **Fonts**: Cormorant Garamond (display) + Montserrat (body)
- **Colors**: `#0A0A0A` dark · `#C9A84C` gold · `#F5F0E8` warm white
- **Fully responsive**: Mobile, tablet, desktop
- **Contact form**: Routes via WhatsApp for instant delivery

---

## 📞 Contact Details on Site

| Channel | Details |
|---|---|
| Personal Phone / WhatsApp | +251 913 554 296 |
| Metro Office | +251 938 060 606 |
| Metro Email | sales@metrorealestateet.com |
| Metro Office Address | 2nd Floor, Sur Construction Bldg, Africa Ave, Addis Ababa |
| Metro Website | [metrorealestateet.com](https://www.metrorealestateet.com) |

---

*Built with care for Sofonias Teshome · 2025*
