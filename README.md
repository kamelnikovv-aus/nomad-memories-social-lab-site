# Nomad Memories Social Lab public site

This folder is a standalone, static GitHub Pages site. It contains only public HTML/CSS and `.nojekyll`; do not copy files from the private Social Content Lab project into this repository.

## Before publishing

1. Verify that the contact email on all three HTML pages is current and monitored by Nomad Memories.
2. Review the policy text against the actual operating setup and approved platform permissions.
3. Create a **new public repository** for these files only, then enable GitHub Pages from the root of the default branch. Do not add the existing project's source code, database, token files, secrets, or configuration.
4. Confirm that the home, Terms, and Privacy URLs return HTTP 200 without authentication before entering them in TikTok Developer Portal.

## TikTok URL verification file

If TikTok provides a verification file, add it at the exact path TikTok specifies (the repository root for a site-prefix root URL) using its exact supplied filename and contents. Publish it with the site and check its public URL before submitting verification. Do not fabricate a verification file or assume its required filename.
