# StepLock Website (GitHub Pages)

This folder contains a simple static site for Privacy and Support.

## Deploy (GitHub Pages - Project Pages)

1. Create a new repository on GitHub named `steplock-site` under your account (`USERNAME`).
2. Push these files:

```bash
cd website
git init
git add .
git commit -m "Publish StepLock site"
git branch -M main
git remote add origin https://github.com/USERNAME/steplock-site.git
git push -u origin main
```

3. In GitHub → repo Settings → Pages:
   - Source: `Deploy from a branch`
   - Branch: `main` / `/ (root)`

4. After it builds, your URLs will be:
   - Home: https://USERNAME.github.io/steplock-site/
   - Privacy: https://USERNAME.github.io/steplock-site/privacy.html
   - Support: https://USERNAME.github.io/steplock-site/support.html

## Optional: Custom domain
- Add a `CNAME` file at the repository root containing your domain (e.g., `steplock.app`).
- Point your DNS (CNAME) to `USERNAME.github.io`.
