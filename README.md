# luup-site

Public legal pages for the Luup mobile app, served by GitHub Pages:

- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Use
- `delete-account.html` — account deletion instructions (required by Google Play)

The app links to these URLs (`src/constants/links.ts` in the app repo), so
keep the file names stable.

The contact address is the placeholder `support@luup.example` until a real
support inbox exists. To set it everywhere:

```bash
sed -i 's/support@luup\.example/YOUR@ADDRESS/g' *.html
```

These pages are a plain-English draft based on what the app actually
collects — not legal advice.
