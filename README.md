# kyno.az

The KYNO website. Plain HTML and CSS, hosted on GitHub Pages. No build step:
whatever is in the `main` branch is the live site.

## Pages

| Page | File |
|---|---|
| Home | `index.html` |
| Biz kimik? | `haqqimizda/index.html` |
| Podkastlar | `podkastlar/index.html` |
| Instagram-da KYNO | `instagram/index.html` |
| Bizə dəstək olun! | `destek/index.html` |
| Əlaqə | `elaqe/index.html` |

The header, menu and contact block are repeated in every page, so a change to
one of them has to be made in each file.

## Changing things

- **Text or links:** edit the page's file. On GitHub, open the file, click the
  pencil icon, change it, and press **Commit changes**. The site updates in
  about a minute.
- **Colours, fonts, spacing:** `assets/css/style.css`. The `:root` block near the
  top holds the colours.
- **Images:** `assets/img/`.

## Instagram film strip

On the Instagram page each frame shows a countdown number until a post is put
in it. The comment above the strip in `instagram/index.html` shows the line to
use for a post.

## Fonts

Big Shoulders Display and Literata, both under the SIL Open Font License and
served from `assets/fonts/` so the site makes no requests to third parties.
