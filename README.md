# Stepory Privacy Policy (GitHub Pages)

This folder contains the privacy policy page for the Stepory app, set up for hosting on **GitHub Pages** (github.io).

## How to publish

1. **Create a new GitHub repo** for the privacy policy (e.g. `stepory-privacy` or `stepory-privacy-policy`).

2. **Copy the contents of this folder** into the **root** of that repo:
   - `index.html` must be at the repo root so GitHub Pages serves it at the site root.

3. **Push to GitHub** (e.g. push `index.html` and this README to the `main` branch).

4. **Enable GitHub Pages:**
   - Repo → **Settings** → **Pages**
   - Under **Build and deployment**, set **Source** to **Deploy from a branch**
   - **Branch:** `main` (or `master`), **Folder:** `/ (root)`
   - Save. GitHub will build and deploy; the site may take 1–2 minutes to appear.

5. **Your privacy policy URL** will be:
   - **Project site:** `https://<your-username>.github.io/<repo-name>/`  
     Example: `https://johndoe.github.io/stepory-privacy/`
   - **User/org site:** If the repo is named `<username>.github.io`, the URL is `https://<username>.github.io/`

6. **Use this URL in Google Play Console:**  
   App content → Privacy policy → paste the URL (e.g. `https://yourusername.github.io/stepory-privacy/`).

## Before publishing

- In `index.html`, replace `privacy@stepory.app` with your real support or privacy email (see the Contact Us section and the HTML comment above it).
