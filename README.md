# Forge Fit Public Site

This folder contains the publishable static version:

- `index.html`

You can upload this folder to any static host that supports a plain `index.html`, such as Netlify, Vercel static deploys, GitHub Pages, Cloudflare Pages, or shared web hosting.

Current data behavior:

- User profile, generated plan, session completion, export data, and check-ins are stored in the visitor's browser with `localStorage`.
- Visitors do not share data with each other.
- Data will not sync across devices until login and a backend database are added.

Next backend step:

- Add authentication.
- Store profiles, plans, completions, and check-ins in a database.
- Add account-level export and delete controls before collecting public user data server-side.
