# MLxDB.github.io

Source for <https://mlxdb.github.io>. Built with Hugo + the Wowchemy research-group theme. Pushes to `main` are auto-built and deployed by GitHub Actions (`.github/workflows/hugo.yml`).

## How to edit

```bash
git pull                 # sync first
# edit files under content/
git add . && git commit -m "..."
git push                 # Actions builds and deploys, ~1-2 min
```

No local Hugo install needed. Watch deploys at the **Actions** tab.

### Where things live

| Want to change | File |
|---|---|
| Add a publication | `content/publication/<id>/index.md` (+ optional `cite.bib`, `featured.jpg`) |
| Add a news post | `content/post/<yy-mm-dd-title>/index.md` |
| Add a member | `content/authors/<Name>/_index.md` + `avatar.jpg` |
| Reorder members in a group | add `weight: <number>` in their `_index.md` (smaller = earlier) |
| Home page copy | `content/home/welcome.md`, `intro.md`, `news.md` |
| Project page | `content/project/<name>/_index.md` |
| Top nav menu | `config/_default/menus.yaml` |
| Site title, baseURL, etc. | `config/_default/config.yaml`, `params.yaml` |

### Local preview (optional)

Only needed if you want to see the result before pushing:

```bash
hugo server                # http://localhost:1313
```

Requires Hugo extended `v0.110.0` and Go (matches the version pinned in the workflow).

## Branches

- `main` — Hugo source, what you edit. Default branch.
- `master` — frozen snapshot of the old hand-deployed static site. Kept for history; don't push to it.

## Deployment

GitHub Pages is configured with **Source: GitHub Actions**. The workflow (`hugo.yml`) builds with Hugo and deploys via `actions/deploy-pages`. The `github-pages` environment must allow `main` (Settings → Environments → github-pages → Deployment branches).

---

Theme: [wowchemy/starter-hugo-research-group](https://github.com/wowchemy/starter-hugo-research-group).
