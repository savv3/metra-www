# metra-www

The marketing website for [Metra](https://github.com/savv3/Metra), in
Swedish. It is plain HTML and CSS with no build step, no JavaScript, no
cookies, no external fonts and no tracking.

```
index.html     the page
style.css      the styles, with the app's colours and a dark theme
favicon.svg    the Metra logo, copied from the app
img/           screenshots of the app, light and dark (WebP)
```

## Preview

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8080
```

## Publish

Any static host works (GitHub Pages, Cloudflare Pages, Netlify, or a plain
web server). Upload the files as they are. For GitHub Pages with a custom
domain, add a `CNAME` file with the domain.

## Screenshots

The screenshots are taken from a Metra install with made-up demo data, at
1280×800 for the desktop pages and 390 px wide (2× pixel density) for the
phone pages, in both light and dark mode. Each image has a `-light` and a
`-dark` version, and the page picks the one matching the visitor's setting.
When the app's look changes, retake them the same way and save them as WebP.

## Before launch

- Replace the placeholder address `kontakt@example.com` in `index.html`.
- Add the domain (and `CNAME` if needed).
