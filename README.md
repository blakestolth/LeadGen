# Auto Pre-Approval Landing

A single-file landing page deployed to Netlify via Git.

## Quick Deploy

1. Push this folder to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/auto-preapproval-landing.git
   git push -u origin main
   ```

2. In Netlify: **Add new site → Import an existing project → GitHub → select repo**  
   - Build command: *(leave empty)*  
   - Publish directory: `/`

3. Forms: Netlify will auto-detect the `<form name="lead-form" data-netlify="true">`.  
   - Submissions: **Netlify → Forms**.  
   - Notifications: **Forms → Settings & usage**.

## Local edits
- Edit `index.html` to change copy/design.
- `thank-you.html` is used for no-JS fallback success page.
- Optional: add `/assets/` for local images and update references.
