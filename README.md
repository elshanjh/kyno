# kyno.az

The KYNO website, in Azerbaijani and English. Plain HTML and CSS, hosted on
GitHub Pages. No build step: whatever is in the `main` branch is the live site.

## Pages

| Page | Azerbaijani | English |
|---|---|---|
| Home | `index.html` | `en/index.html` |
| About | `haqqimizda/index.html` | `en/about/index.html` |
| Podcasts | `podkastlar/index.html` | `en/podcasts/index.html` |
| Social media | `sosial-media/index.html` | `en/social/index.html` |
| Support | `destek/index.html` | `en/support/index.html` |
| Contact | `elaqe/index.html` | `en/contact/index.html` |

The header, menu and contact block are repeated in every page, and each page
exists once per language, so a change to shared text has to be made in each file.

## Changing things

- **Text or links:** edit the page's file. On GitHub, open the file, click the
  pencil icon, change it, and press **Commit changes**. The site updates in
  about a minute.
- **Colours, fonts, spacing:** `assets/css/style.css`. The `:root` block near the
  top holds the colours.
- **Images:** `assets/img/`.

## Instagram posts

The film strip on the home and social media pages embeds posts straight from
Instagram. To change a post, find its line in the page (it contains
`instagram.com/p/...`) and replace the code after `/p/` in both places with the
code from the new post's link. The embeds load a script from instagram.com.

## Fonts

Big Shoulders Display and Literata, both under the SIL Open Font License and
served from `assets/fonts/`.
