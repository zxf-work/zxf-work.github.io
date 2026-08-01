# Apply the homepage fix

Copy the enclosed files into the repository root, preserving their paths:

- `_layouts/homepage.html`
- `index.md`
- `assets/css/site.css`
- `assets/css/publications.css`
- `_config.yml`

The existing `_includes/publications.md` and `_data/publications.yml` remain unchanged.

Then commit and push:

```bash
git add _layouts/homepage.html index.md assets/css/site.css assets/css/publications.css _config.yml
git commit -m "Fix homepage layout and styling"
git push
```

The layout adds a build-revision query parameter to the CSS URLs, so browsers should not keep displaying a stale stylesheet after deployment.
