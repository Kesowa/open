# Kesowa — open source directory

The source for Kesowa's open-access page, a public directory of the
repositories we have opened up.

**Live at: https://kesowa.github.io/open/**

## What this is

Kesowa builds ARU, a platform for flying drone missions and turning what comes
back into maps. Eleven of our repositories are public, and this page lists them
in one place with a description of what each one is for, so someone outside
Kesowa can tell at a glance what is here.

## Structure

The whole site is `index.html` — one self-contained file with inline styles and
no build step. Fonts come from Google Fonts; nothing else is fetched.

To add or change an entry, edit the relevant `<div class="entry">` block. Each
entry has two parts:

- `entry__rail` — the repository name, its language, its license, and a status
  badge (`status--active`, `status--prototype` or `status--reference`)
- `entry__body` — the description, plus an optional `<span class="flag">` for a
  caveat a reader needs before they clone it

## Publishing

GitHub Pages serves `master` from the repository root. Pushing to `master`
updates the site.

## License

MIT — see [LICENSE](LICENSE).
