# self-host-blog

This repository contains the beginnings of a personal blog that will
eventually be built with [Hugo](https://gohugo.io/).

For now there is a **very simple "Hello World" website** that is
served by GitHub Pages.  The static content lives under the `docs/`
directory so that GitHub can publish it automatically from the `main`
branch.

## Getting started

1. Clone the repository and make your changes.
2. Add content or switch to Hugo when you're ready – see the
	`config.toml` for a minimal starting point.
3. Push to `main`. GitHub Pages will serve whatever is in `docs/`.

## Hugo readiness

The `config.toml` file is a bare‑bones Hugo configuration.  When you
run `hugo` locally (or via CI) the generated site can be placed into
`docs/` for publishing.  A workflow template is included to help with
that.

Feel free to replace the placeholder files with a full Hugo site
later – the current structure is just enough to get the Pages site
up and running.
