COP31 Europe Desk - static site
================================
Files: index.html (page), data.json (all content), fonts/ (self-hosted, open licence).
No build step, no cookies, no third-party requests.

The page loads data.json from the same folder, so open it through a web host,
not by double-clicking the file.

To update content: edit data.json only, then re-upload it.

Quick hosting options
- GitHub Pages: put these files in a repository, then Settings > Pages >
  Deploy from branch (main, /root). Supports automatic daily updates.
- Netlify Drop: drag this folder onto app.netlify.com/drop. Fastest, but
  updates mean re-dragging the folder.
- Codeberg Pages (Berlin-based non-profit): push to a repo named "pages".
