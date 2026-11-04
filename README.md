# overtime

Static site. No build step, no settings to change.

Upload: on github.com create a repo named `<your-username>.github.io`, click "uploading an existing file",
drag everything in this folder into the page, commit. Then Settings > Pages > Deploy from a branch > main / root.

Notes
- Serve it from a domain root (a `<user>.github.io` repo or a custom domain), not from `user.github.io/repo-name/`.
- The Launch form and Connect button are UI only; there is no backend (`/api/...` calls 404 and pages show empty states).
- Geist fonts load from the jsDelivr CDN.
