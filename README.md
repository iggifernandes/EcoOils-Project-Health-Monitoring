# EcoOils Mentari — Health Record (landing page + admin)

- `index.html` — landing page linking to the Blood Pressure and Alcohol tools. Set `BLOOD_PRESSURE_URL` and `ALCOHOL_URL` near the top of its script to the live GitHub Pages addresses of the two tool repos.
- `admin.html` — admin trends dashboard for both tools (opened from the **Admin** button on every page). Reads the same Google Sheet through the Apps Script web app in `SCRIPT_URL`.

The admin key is **not** in any file here. It lives in the Apps Script (Script Properties → `ADMIN_KEY`) and is checked there. Until the Script enforces it, the admin page shows totals only (no names or individual readings).

Keep `index.html`, `admin.html` and `logo.png` in the same folder. Current version: 1.1.0 (shown top-right on every page).
