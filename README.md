# GAJE 777 — tattoo portfolio

Static site (index.html + styles.css). No build step.

## Adding photos
Drop JPGs into `images/` with these exact names; empty slots show a placeholder until a file exists.

- `images/portrait.jpg` — about portrait (3:4)
- `images/flash-01.jpg` … `flash-08.jpg` — flash grid (4:5)
- `images/work-01.jpg` … `work-09.jpg` — healed work grid (4:5)

Need more slots? Change `data-count` on the grid in index.html.

## Editing text
Search index.html for `[ EDIT ME ]` / `[ edit ]` (bio, style, deposit, instagram handle, location).

## Deploy
`vercel deploy --prod`
