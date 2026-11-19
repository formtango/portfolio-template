# Portfolio template

A clean, fast, one-page portfolio in plain HTML and CSS, with a contact form that works on any static host. No build step, no framework, no JavaScript you need to understand.

**[Live demo](https://formtango.github.io/portfolio-template/)**

- Light and dark themes with a switch
- Intro, selected work, about with a timeline, and contact
- A working contact form, handled by [FormTango](https://formtango.com): messages arrive in an inbox and by email, with spam filtered out
- Responsive, accessible, about 10 KB before fonts

## Use it

1. Click **Use this template** (or download the three files).
2. Edit `index.html`: your name, projects and links.
3. Change the colours at the top of `style.css` if you like.
4. Host it anywhere: GitHub Pages, Netlify, Vercel, Cloudflare Pages.

## Make the form work

1. Get a form id. Sign up free at https://formtango.com (100 submissions a month), or create one with no account:

   ```bash
   curl -X POST https://formtango.com/api/v1/claims \
     -H "Content-Type: application/json" -d '{"name":"Contact form"}'
   ```

2. In `index.html`, replace `YOUR_FORM_ID` with it.

That's all. Until you do, the form runs in demo mode and tells visitors so.

## Customise

- **Project images:** replace the coloured `.cover` blocks with `<img>` tags.
- **Colours and fonts:** all in the first few lines of `style.css`.
- **More form fields:** add inputs with a `name`; they are sent automatically.

## License

MIT. No attribution needed, though the footer link is appreciated.
