# ayeshaadesign portfolio

Portfolio website for Ayesha Parvaiz, senior graphic designer.

| File | What it is |
|---|---|
| `index.html` | Live version of the site |
| `test.html` | Test version: five-shade burgundy palette, gradients, light mode by default with a dark mode toggle, responsive hero sphere, mobile menu |
| `colour-preview.html` | Palette preview with a switcher |
| `img/`, `video/`, `js/` | Images, reels and the neon tubes script |

## Run it on your computer

You need an internet connection for the fonts and the 3D library. Then pick one way:

**Python (Windows, Mac, Linux)**

```bash
cd ayeshaadesign-portfolio
python -m http.server 8000
```

Open http://localhost:8000 for the live site, or http://localhost:8000/test.html for the test version.

**VS Code**

Install the "Live Server" extension, open this folder, right-click `index.html` and choose "Open with Live Server".

**Node.js**

```bash
npx serve ayeshaadesign-portfolio
```

Opening the HTML file by double-clicking works for most of the page. The Reels neon tubes effect needs one of the local servers above, because browsers block JavaScript modules on `file://`.
