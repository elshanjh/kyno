# kyno.az

The KYNO website. Plain HTML and CSS, hosted on GitHub Pages. No build step:
whatever is in the `main` branch is the live site.

## Changing things

| What | Where |
|---|---|
| Any text or link | `index.html` |
| Colours, fonts, spacing | `assets/css/style.css` (the `:root` block near the top holds the colours) |
| Images | `assets/img/` |

To edit on GitHub: open the file, click the pencil icon, change it, and press
**Commit changes**. The site updates in about a minute.

## Images

- `hero-wide.jpg` and `hero-tall.jpg`: the banner at the top (wide screens and phones).
- `kim-sorusdu.jpg`, `titrlardan-sonra-nagara.jpg`: podcast artwork.
- `logo.svg`, `logo-black.svg`: the wordmark, traced from the podcast artwork.
  Replace with an SVG exported from the original logo file when available.

## Instagram film strip

Each frame shows a countdown number until a post is put in it. To add a post,
save its picture in `assets/img/` and replace the frame's content in
`index.html`, as described in the comment above the strip.

## Fonts

Big Shoulders Display and Literata, both under the SIL Open Font License and
served from `assets/fonts/` so the site makes no requests to third parties.
