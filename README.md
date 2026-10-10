# OCHH HAIRS (mock site)

A one-file storefront for OCHH HAIRS: premium wigs, bundles, closures and frontals.
Everything (HTML, CSS and JavaScript) lives in **`index.html`**. There is no build step and nothing to install.

## Deploy

**GitHub Pages:** Settings, then Pages, then *Deploy from a branch*, branch `main`, folder `/ (root)`.
The site is then at `https://rexfi-cyber.github.io/ochhhairs.mock/`.

**Netlify, Vercel or Cloudflare Pages:** connect this repo (no build command, publish directory `/`),
or drag `index.html` into Netlify Drop.

**Locally:** double-click `index.html`.

## Edit your details

Open `index.html` and search for `CONFIG` near the bottom (inside `<script>`):

- `whatsapp`: your number in international format, no `+` (for example `2348012345678`)
- `email` and `social` links
- `PRODUCTS`: names, prices, and `img: "https://..."` for real photos
- `REVIEWS`: add real customer reviews

Orders are sent to WhatsApp from the cart. The newsletter form still needs to be connected
to an email service (Mailchimp, Brevo, Formspree).
