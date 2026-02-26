# Self-hosted Hobby Journal

This repository contains a Hugo website used to chronicle and document 
my personal hobby projects.  The site is styled with a custom **pastel
color palette** and follows a modern, minimalist layout.

Static content is generated into the `docs/` directory so GitHub Pages
can serve the site directly from the `main` branch.

## Local Development

1. Install [Hugo](https://gohugo.io/getting-started/install/).
2. Clone this repository and run:

```bash
hugo server
```

3. Open `http://localhost:1313` in your browser to preview changes.
4. Add new posts or pages with `hugo new <section>/<name>.md`.

## Building for Production

Run `hugo` in the project root. The generated site will appear in
`docs/`. Commit and push those files to deploy via GitHub Pages.

## Theme and Styling

A lightweight local theme called `pastel-theme` lives under
`themes/pastel-theme`.  It contains layouts and a stylesheet
(`static/css/styles.css`) that implements the modern pastel look.
Feel free to edit or extend the CSS and templates as the site grows.

## Content Structure

- `content/_index.md` – home page introduction
- `content/posts/` – hobby journal posts

The menu can be managed via `config.toml` using the `[menu.main]`
entries.

---
