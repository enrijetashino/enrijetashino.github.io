# enrijetashino.github.io

Personal academic website of Enrijeta Shino, published with GitHub Pages at
<https://enrijetashino.github.io>.

The whole site is one page. Everything you might want to change is in one of these files:

| To change...                          | Edit                          |
|---------------------------------------|-------------------------------|
| The bio, CV path, or photo path       | `index.html` (top of the file) |
| Publications and book chapters        | `_data/publications.yml`      |
| Working papers                        | `_data/working_papers.yml`    |
| Media coverage                        | `_data/media.yml`             |
| Teaching, contact details             | `index.html`                  |
| Email, Scholar/GitHub/X links         | `_config.yml`                 |
| Colors and fonts                      | `assets/style.css`            |

## Common updates

**New CV.** Upload it as `assets/cv_eshino.pdf`, replacing the old file. Keeping the
same file name means every link to the CV (on the site and anywhere you have shared it)
always opens the latest version.

**New publication.** Copy any entry in `_data/publications.yml`, paste it at the top of
the `articles` list, and edit it. Only `year`, `authors`, `title` and `journal` are
required; `volume`, `pages` and `doi` are optional. Your name is bolded automatically.
If it was a working paper, delete it from `_data/working_papers.yml`.

**New photo.** Replace `assets/photo.jpg` (portrait shape, about 720 x 900 pixels,
under 200 KB).

Edits made on github.com go live about a minute after you commit them.
