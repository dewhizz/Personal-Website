# Personal Website — Lewis Kimari

This is the source for Lewis Kimari's personal portfolio website.

## Deploy to Netlify
Recommended options:

1) Connect a GitHub repository to Netlify
   - Push this repository to GitHub (create a repo like `lewis-portfolio`)
   - In Netlify dashboard, click "New site from Git" → GitHub → select the repo
   - Set build command: (none required for static site)
   - Set publish directory: `/` or `.` (root)

2) Quick deploy with Netlify CLI (local)
   - Install Netlify CLI: `npm install -g netlify-cli`
   - Build (if you have a build step) then run: `netlify deploy --dir=./ --prod`

3) Drag and drop
   - Zip the site (or select `index.html` and assets) and drag onto Netlify Sites -> "Deploy site".

## Files added
- `netlify.toml` — Netlify site configuration
- `.gitignore` — standard ignores
- `README.md` — this file

## Notes
- If you want me to push files and create the repo structure locally, tell me and I can create a local git repo and commit the changes for you. I cannot create the remote GitHub repo or connect Netlify on your behalf without your credentials.