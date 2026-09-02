# Your portfolio site

Two files make this whole site:
- `index.html` — the content and structure
- `styles.css` — all the styling

## Editing the content

Open `index.html` in any text editor. Everything you need to change is wrapped in `[brackets]` — replace those with your real info:
- Your name (in the header, hero, and footer)
- Your role/tagline
- Your 4 project entries (title, year, description, link)
- Your about text and skills
- Your email, LinkedIn, and GitHub links

Feel free to add or remove `<li class="project">...</li>` blocks in the Work section — the numbering and layout will keep working with more or fewer projects.

## Deploying on Netlify

**Fastest way (drag and drop):**
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag this whole folder (containing `index.html` and `styles.css`) into the browser window
3. Netlify gives you a live URL immediately

**To use your own domain name**, go to Site settings → Domain management once it's deployed, and follow Netlify's prompts to connect a domain you own (or buy one through Netlify).

## The contact form

The form is wired up to use **Netlify Forms**, which means once it's deployed on Netlify, form submissions will show up in your Netlify dashboard (Site → Forms) automatically — no backend or email server needed. It won't work in a locally opened file, only once deployed.

## Fonts

The site uses two Google Fonts (Fraunces for headings, IBM Plex Sans for body text), loaded via a `<link>` in `index.html`. No installation needed — they load from Google's CDN.
