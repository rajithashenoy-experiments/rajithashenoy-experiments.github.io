# My Writing

A minimal Jekyll blog, set up to deploy on GitHub Pages with zero build config.

## Structure

- `_config.yml` — site title, description, author. Edit this first.
- `_posts/` — your posts live here. File name format: `YYYY-MM-DD-title.md`
- `about.md` — the About page.
- `index.html` — homepage, lists all posts automatically. You shouldn't need to touch this.
- `_layouts/` — page templates (default + post). Edit `assets/css/style.css` to restyle.

## Writing a new post

Create a file in `_posts/` named like `2026-07-06-my-post-title.md`:

```markdown
---
title: "My Post Title"
---

Your content here, in Markdown.
```

That's it — no build step needed locally if you just want to push and let GitHub build it.

## Previewing locally (optional but recommended)

If you have Ruby installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000

## Deploying to GitHub Pages

1. Push this folder to a new GitHub repo (e.g. `yourusername/yourusername.github.io` for a root domain, or any repo name for a project site).
2. In the repo, go to **Settings → Pages**.
3. Under "Build and deployment," set **Source** to "Deploy from a branch," and pick `main` (or `master`) and `/ (root)`.
4. Save. GitHub will build the Jekyll site automatically — no Actions/CI config needed.

### Using your existing custom domain

1. In **Settings → Pages**, enter your domain under "Custom domain." This creates a `CNAME` file in your repo automatically (or add one yourself containing just your domain, e.g. `yourdomain.com`).
2. At your domain registrar, add DNS records pointing to GitHub Pages:
   - For an apex domain (`yourdomain.com`): four `A` records pointing to
     `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - For a `www` subdomain: a `CNAME` record pointing to `yourusername.github.io`
3. DNS changes can take a few minutes to a few hours to propagate. Once live, check "Enforce HTTPS" back in Settings → Pages.

## Notes

- `site.url` and `baseurl` in `_config.yml` are left blank, which is correct once you're using a custom domain. If you deploy to `yourusername.github.io/reponame` instead, set `baseurl: "/reponame"`.
- RSS feed is available automatically at `/feed.xml` via `jekyll-feed`.
