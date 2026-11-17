# richardsouvenir.github.io

Single-page academic site for Richard Souvenir. It is built by GitHub Pages (Jekyll), and every commit to `main` publishes within about a minute.

## Common edits (all in the GitHub web editor: open the file, click the pencil, then Commit)

| To change… | Edit |
|---|---|
| Add a news item | `_data/news.yml`: add an item at the **top** with `date: YYYY-MM-DD` and `text:` |
| Selected publications | `_data/publications.yml` |
| Lab members / alumni | `_data/people.yml` |
| Titles, intro, "What I work on", links, contact text | `_data/profile.yml` |
| Headshot | Upload a square photo as `images/headshot.jpg` (Add file → Upload files) |
| Publication thumbnails | Upload to `images/pubs/`, then add `image: /images/pubs/name.jpg` to the paper |

The home page shows the 6 most recent news items, and older items go under "Older news". Text fields accept Markdown links: `[label](https://...)`.

## Layout
- `index.html`: the page template
- `assets/css/style.css`: styles (colors are set at the top)
- `assets/fonts/`: self-hosted Newsreader and Inter fonts
