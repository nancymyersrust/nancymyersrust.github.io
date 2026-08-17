# Nancy Myers Rust — Author Site

Built with Jekyll. GitHub Pages rebuilds the site automatically every time
you save a change. No software to install.

## Where to edit things

| What you want to change | Which file |
|---|---|
| Email, Substack link, Instagram link, agent info | `_config.yml` |
| Bio text, the Jason story, contact line, newsletter blurb | `index.html` (look for `<!-- EDIT HERE -->`) |
| Published pieces (titles, links, dates) | `_data/writing.yml` |
| Photos | replace files in `images/` (keep the same filenames) |
| Colors, fonts, spacing | `assets/css/style.css` |

## Adding a published piece

In `_data/writing.yml`, add a block like this at the top of the list:

```yaml
- title: "Your Essay Title"
  publication: "Magazine Name"
  date: "March 2026"
  genre: "Essay"                            # or "Fiction"
  url: "https://link-to-the-piece"           # leave "" if print-only
  publication_url: "https://magazine-site"   # links the magazine name
```

## When your book sells

Tell Claude (or any developer) you want a book section back — the site was
built so one can drop in above the Writing section.

## Publishing a change

Edit the file on GitHub.com (pencil icon), click "Commit changes," and the
live site updates in a minute or two.
