# Bookin-AI Portfolio (GitHub Pages Ready)

This is a static, production-optimized landing page.

## Publish on GitHub (simple)

1. Create a new GitHub repo.
2. Upload/push this entire folder to the repo.
3. In GitHub: `Settings -> Pages`.
4. Under **Build and deployment**, set **Source** to **GitHub Actions**.
5. Push to `main` (or re-run the workflow once).  
   The workflow in `.github/workflows/pages.yml` deploys automatically.

### One-command publish (local terminal)

```bash
./publish-github.sh https://github.com/afilmer-ai/bookin-ai.git main
```

Your live URL will be:
- `https://<your-username>.github.io/<repo-name>/` (project page), or
- your custom domain if you configure one.

## Local preview

From this folder:

```bash
ruby -run -e httpd . -p 4173
```

Then open `http://127.0.0.1:4173/`.

