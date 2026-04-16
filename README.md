# Amakin — Coming Soon

"Coming Soon" landing page for [amakin.ma](https://amakin.ma).

## Stack

- Static HTML/CSS
- Nginx Alpine (Docker)
- Deployed via Coolify on Hetzner VPS

## Local Development

```bash
# Build
docker build -t amakin-coming-soon .

# Run
docker run -p 8080:80 amakin-coming-soon

# Open http://localhost:8080
```

## Deployment

Deployed automatically via Coolify when pushing to `main`.
