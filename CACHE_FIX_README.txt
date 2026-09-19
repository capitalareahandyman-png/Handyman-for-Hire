# Handyman for Hire Cache Fix

Upload these files to the ROOT of your GitHub Pages repository and replace the existing files.

IMPORTANT:
- Replace index.html
- Replace service-worker.js
- Upload thanks.html
- Keep manifest.webmanifest, README.md, and .nojekyll

This hotfix clears the old cached version of the site and disables the old cache-first service worker.

After GitHub Pages rebuilds:
1. Open the live site.
2. Refresh once.
3. You should see the new form with:
   - Email required
   - Preferred contact method
   - Photo upload
   - SEND MY SERVICE REQUEST button
4. Submit one test form.
5. Confirm the FormSubmit activation email sent to capitalareahandyman@gmail.com.
