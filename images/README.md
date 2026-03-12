# HIPNOIDAL
### Butoh Dance · Shadow Theatre · Live Music
*Pierina Lategola, Ada Gomiz & Tatiana Zuccolotto*

---

A portfolio website in **5 languages** (English, Spanish, Danish, Norwegian, Swedish).
Dark, nocturnal design — ready for GitHub Pages.

## 🌑 Live at GitHub Pages

Once deployed, the site will be at:
`https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

---

## 📁 Setup

### 1. Clone or upload this repo

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

### 2. Enable GitHub Pages

- Go to your repo → **Settings** → **Pages**
- Under *Source*, select **main** branch, **/ (root)**
- Save → your site will be live in ~1 minute

---

## 🖼️ Images

The `index.html` currently links to temporary Notion S3 URLs that **will expire**.

To make images permanent:

1. **Download** the images from your Notion page
2. **Create** an `images/` folder in this repo
3. **Rename** and place them as:

| File | Description |
|------|-------------|
| `images/titulo.png` | Title logo (TITULO_HIP.png) |
| `images/afiche.png` | Main poster (AFICHE_HIPNOIDAL.png) |
| `images/pierina.png` | Pierina portrait (f4.png) |
| `images/ada.png` | Ada portrait (f5.png) |
| `images/tatiana.png` | Tatiana portrait (ttt.png) |
| `images/photo1.jpg` | Performance photo 1 |
| `images/photo2.jpg` | Performance photo 2 |
| `images/photo3.jpg` | Performance photo 3 |
| `images/scenic.png` | Stage diagram |
| `images/photo4.jpg` | Wide performance photo |
| `images/photo5.jpg` | Final closing photo |

4. **Replace** each `src="https://prod-files-secure.s3..."` in `index.html` with `src="images/FILENAME"`.

---

## 🌐 Languages

The language switcher is in the top-right corner: **EN · ES · DA · NO · SV**

All text is fully translated. Switching language updates all content instantly (pure JS, no page reload).

---

## ✏️ Customization

- **Fonts**: Cormorant Garamond + Raleway (via Google Fonts)
- **Colors**: Edit the CSS variables at the top of `<style>`:
  - `--gold` → accent color
  - `--text` → body text color
  - `--bg` → background
- **Add more shows**: Copy a `<li class="show-item">` block in the Presentations section

---

## 📄 License

All content © Hipnoidal / Pierina Lategola, Ada Gomiz & Tatiana Zuccolotto
