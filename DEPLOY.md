# Deploy the website

## Fastest option: Vercel
1. Unzip this folder.
2. Create a GitHub repository and upload all files.
3. Import the repository into Vercel.
4. No build command is required; this is a static site.
5. Deploy.

## GitHub Pages
1. Create a repository.
2. Upload `index.html`, `vercel.json`, `package.json`, and the other files.
3. Enable GitHub Pages from Settings → Pages.
4. Select the main branch and root folder.

## Local preview
Run:

    python -m http.server 4173

Then open http://localhost:4173

## Production recommendation
This version is a static prototype. For a production student platform, move curriculum, question banks, student accounts, attempts, teacher analytics and markschemes into a database/backend. Keep the course-guide mapping as the authoritative curriculum layer.
