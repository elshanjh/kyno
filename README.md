# kyno.az

The KYNO website. Plain HTML and CSS, hosted on GitHub Pages. No build step:
whatever is in the `main` branch is the live site.

## Changing things

| What | Where |
|---|---|
| Any text or link | `index.html` |
| Colours, fonts, spacing | `assets/css/style.css` (the `:root` block at the top holds the colours) |
| Images | `assets/img/` |

To edit on GitHub: open the file, click the pencil icon, change it, and press
**Commit changes**. The site updates in about a minute.

## Images still to add

The site works without these, using text in their place.

- **Logo:** save the white logo as `assets/img/logo.svg` (or `.png`), then in
  `index.html` replace the word `kyno` inside the `wordmark` link with
  `<img src="assets/img/logo.svg" alt="KYNO">`.
- **Podcast covers:** save them as `assets/img/kim-sorusdu.jpg` and
  `assets/img/titrlardan-sonra-nagara.jpg`, then replace each cover's `<span>`
  with the `<img>` tag shown in the comment above it.
- **Hero still (optional):** a wide film still can sit behind the title. Save it
  in `assets/img/` and it can be wired in from `style.css` (`.screen`).

## Fonts

Big Shoulders Display and Literata, both under the SIL Open Font License and
served from `assets/fonts/` so the site makes no requests to third parties.
