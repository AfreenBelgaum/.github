# 🚀 GitHub Actions Beginner-to-Pro Template Pack

This pack contains **10 ready-to-use GitHub Actions workflow templates**.  
Copy any of these `.yml` files into your repository under `.github/workflows/` to start using them.

---

## 📂 Templates Included

### 1. 01-hello-world.yml
- Minimal workflow that prints "Hello GitHub Actions!"
- Perfect first test to confirm Actions are enabled.

### 2. 02-triggers.yml
- Demonstrates different triggers:
  - `push`
  - `pull_request`
  - `schedule` (cron jobs)
  - `workflow_dispatch` (manual trigger)

### 3. 03-multi-os.yml
- Run jobs across **Linux, Windows, and macOS** runners.
- Useful for cross-platform testing.

### 4. 04-node-tests.yml
- Installs dependencies and runs `npm test`.
- Great for Node.js/JavaScript projects.

### 5. 05-secrets-env.yml
- Demonstrates **secrets** and **environment variables**.
- Example: Using `secrets.MY_API_KEY`.

### 6. 06-cache.yml
- Uses `actions/cache` to speed up builds by caching dependencies.
- Example: caching `node_modules`.

### 7. 07-matrix.yml
- Matrix strategy for running tests on multiple Node versions (14, 16, 18).
- Useful for libraries that support multiple runtimes.

### 8. 08-deploy-gh-pages.yml
- Deploys static site to **GitHub Pages**.
- Example: publish HTML files from `./public`.

### 9. 09-advanced.yml
- Shows **conditional workflows**.
- Example: Deploy only if branch = `main`.

### 10. 10-full-pipeline.yml
- Full CI/CD pipeline:
  - Runs on `push` and `pull_request`
  - Linting + Testing + Deployment
  - Example: Node.js project with deploy step

---

## ✅ How to Use
1. Pick a template file.
2. Copy it into `.github/workflows/` in your repository.
3. Commit and push changes.
4. Check the **Actions tab** in GitHub to see it run.

---

## 🔒 Tips
- Always store API keys/tokens in **GitHub Secrets** (`Settings → Secrets → Actions`).
- Use `workflow_dispatch` for manual runs.
- Add status badges to your `README.md` like:

```md
![CI](https://github.com/your-username/your-repo/actions/workflows/10-full-pipeline.yml/badge.svg)
```

---

Happy Automating! 🎉
