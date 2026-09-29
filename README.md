# Amrita SAIL Lab website

Built with Hugo. Every page is a plain Markdown file, so editing is just editing text.

## How to edit

| To change... | Edit this file |
|---|---|
| Homepage (headline, "What We Do", vision/mission) | `content/_index.md` |
| Research page | `content/research/index.md` |
| Team & collaborators | `content/team/index.md` |
| Projects | `content/projects/index.md` |
| Publications | `content/publications/index.md` |
| Contact details | `content/contact/index.md` |
| Top menu | `config/_default/menus.yaml` |
| Site name, colors, footer, copyright | `config/_default/params.yaml` |
| Logo / icon | `assets/media/logo.svg`, `assets/media/icon.png` |

**Easiest way:** open a file on GitHub, click the pencil icon, change the text, and commit. The site rebuilds and redeploys automatically (`.github/workflows/deploy.yml`).

**Add a new page:** create `content/<name>/index.md` with a `title:` header, then add a link in `menus.yaml`.

## Run locally

```
pnpm install
pnpm dev
```

Requires Hugo and Node/pnpm.

## Credits

Built on the open-source [Hugo Blox](https://hugoblox.com) framework (MIT, see `LICENSE.md`).
