# MAGDIEL ¢ents

A writing practice, a signal, and a sentence.

## Site Structure

```
magdiel-cents/
├── index.html        ← Homepage
├── about.html        ← About
├── archive.html      ← Archive / Blog index
├── post.html         ← Individual post template
├── community.html    ← Community / Forum
├── contact.html      ← Contact
└── README.md
```

## Deploy to GitHub Pages — Step by Step

1. Go to **github.com** and create a free account if you don't have one
2. Click **New repository** (the green button)
3. Name it exactly: `magdiel-cents` (or anything you want)
4. Set it to **Public**
5. Click **Create repository**
6. On the next screen, click **uploading an existing file**
7. Drag all 6 HTML files into the upload area
8. Click **Commit changes**
9. Go to **Settings → Pages** (left sidebar)
10. Under "Source", select **Deploy from a branch**
11. Set branch to **main**, folder to **/ (root)**
12. Click **Save**
13. Wait ~60 seconds — your site will be live at:
    `https://YOUR-USERNAME.github.io/magdiel-cents/`

## Custom Domain (Optional)

If you buy a domain (e.g. magdielcents.com):
1. In GitHub Pages settings, enter your domain under "Custom domain"
2. At your domain registrar, add a CNAME record pointing to `YOUR-USERNAME.github.io`
3. GitHub will auto-provision HTTPS

## Adding New Posts

Duplicate `post.html`, rename it (e.g. `dispatch-02.html`), edit the content.
Add the link to `archive.html` and the homepage dispatches grid.
