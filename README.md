# Clocky – Official Website

Static website for the **Clocky** smart alarm app, operated by Glitgrace.

## Pages Included

| Page | File |
|------|------|
| Home | `index.html` |
| Features | `pages/features.html` |
| About | `pages/about.html` |
| Contact | `pages/contact.html` |
| Privacy Policy | `pages/privacy-policy.html` |
| Terms of Service | `pages/terms-of-service.html` |
| Payment Policy | `pages/payment-policy.html` |
| Refund Policy | `pages/refund-policy.html` |
| Account Deletion | `pages/account-deletion.html` |

**Support email:** [support@glitgrace.in](mailto:support@glitgrace.in)

---

## Host on GitHub Pages (Free)

1. Create a new GitHub repository (e.g. `clocky-website` or `username.github.io`).
2. Upload all files from this folder to the repository root (keep the folder structure).
3. Go to **Settings → Pages**.
4. Under **Source**, select **Deploy from a branch**.
5. Choose branch `main` (or `master`) and folder `/ (root)`.
6. Click **Save**.
7. Your site will be live at:
   - `https://<username>.github.io/<repo-name>/`  
   - or `https://<username>.github.io/` if the repo is named `<username>.github.io`.

### Optional: Custom Domain
In the same Pages settings, add your custom domain and configure DNS as instructed by GitHub.

---

## Local Preview

Open `index.html` in a browser, or run a simple local server:

```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000`.

---

## Structure

```
clocky-website/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── pages/
│   ├── about.html
│   ├── account-deletion.html
│   ├── contact.html
│   ├── features.html
│   ├── payment-policy.html
│   ├── privacy-policy.html
│   ├── refund-policy.html
│   └── terms-of-service.html
└── README.md
```

---

© 2026 Clocky / Glitgrace. All rights reserved.
