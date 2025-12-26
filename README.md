# Vera Website

Static website for Vera - Video Explanations of Recent Events.

## Deploy to GitHub Pages

1. Create a new repository on GitHub
2. Push this folder to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch" and choose `main` branch
5. Your site will be live at `https://yourusername.github.io/repo-name`

## Custom Domain

To use a custom domain:
1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider

## Local Development

Simply open `index.html` in a browser, or use a local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`
