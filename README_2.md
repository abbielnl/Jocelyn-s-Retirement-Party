# 🎓 Celebrating Jocelyn Murimi Kimemba Kirimi

A beautiful retirement celebration website built with love for a dedicated educator, mentor, and guidance counsellor.

> *"A teacher who makes a difference doesn't just teach a subject — she teaches a life."*

---

## 🌐 Live Site

Once deployed on GitHub Pages, the site will be available at:
```
https://yourusername.github.io/your-repo-name
```

---

## 📄 Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero, live countdowns, biography & journey timeline |
| Gallery | `gallery.html` | Full photo album with category filters & lightbox |
| Messages | `messages.html` | Live message wall — visitors can post tributes |
| RSVP | `rsvp.html` | Celebration party RSVP form |
| Styles | `style.css` | Shared warm & cozy design system |

---

## 🗓️ Key Dates

- **Retirement Day** — Wednesday, 25th June 2026
- **Celebration Party** — Saturday, 4th July 2026

---

## 🖼️ Photos Included

| File | Description |
|------|-------------|
| `mum_and_dad.jpg` | Jocelyn & her husband |
| `mum_graduation_1.jpg` | Pan Africa Christian University graduation |
| `mum_graduation_2.jpg` | With fellow graduates |
| `mum_on_vacation.jpg` | Vacation portrait |
| `mum_solo_photo.jpg` | Solo portrait at night |
| `mum_vacation_with_friend.jpg` | Holiday with a friend |
| `mum_with_her_kids_and_randkid.jpg` | With children & grandchild |
| `mum_with_siblings.jpg` | With siblings |
| `mum_with_siblings_2.jpg` | Family gathering |
| `mum_with_students_1-9.jpg` | Various school & student moments |
| `mum_with_teachers.jpg` | With fellow staff |
| `young_mum.jpg` | A young Jocelyn with her child |

---

## 🗄️ Database (JSONBin)

This site uses [JSONBin.io](https://jsonbin.io) to store messages and RSVPs in real time.

| Feature | Bin ID |
|---------|--------|
| Messages | `6a228fe0f5f4af5e29bcc8b4` |
| RSVPs | `6a229007da38895dfe8b41a0` |

The credentials are already embedded in `messages.html` and `rsvp.html` — no further setup needed.

To view responses, log in to [jsonbin.io](https://jsonbin.io) and open your bins.

---

## ✏️ How to Customise

### Update the bio text
Open `index.html` and find the sections marked with `<!-- REPLACE THIS -->` or `<!-- ADD MORE -->` comments. Fill in Jocelyn's story in your own words.

### Add more photos to the gallery
In `gallery.html`, add a new item inside any `gallery-grid` div:
```html
<div class="gallery-item" onclick="openLightbox(this)">
  <img src="your-photo.jpg" alt="Description" loading="lazy" />
  <div class="gallery-overlay">
    <div class="gallery-overlay-text">Your caption here</div>
  </div>
</div>
```

### Add party details to the RSVP page
Open `rsvp.html` and fill in:
- Venue name and location
- Time of the party
- Dress code
- RSVP deadline date

---

## 🚀 Deployment (GitHub Pages)

1. Go to your repository → **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Select **main** branch → **/ (root)**
4. Click **Save**
5. Your site will be live in 1–2 minutes at your GitHub Pages URL

---

## 🛠️ Built With

- Pure HTML, CSS & JavaScript — no frameworks needed
- [Google Fonts](https://fonts.google.com) — Playfair Display, Lora & Nunito
- [JSONBin.io](https://jsonbin.io) — for live messages & RSVP storage

---

Made with ❤️ in honour of **Jocelyn Murimi Kimemba Kirimi** —
a lifetime of shaping hearts and minds.
