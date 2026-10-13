# CAC Boanerges website

Responsive church website with green and blue designs, glass panels, and accessible animations.

## Deploy with Vercel

1. In Vercel, choose **Add New → Project** and import `fisbalog/cac-boanerges`.
2. Keep **Root Directory** at the repository root and **Framework Preset** as **Other**.
3. The included `vercel.json` sets **Output Directory** to `dist`. No build command or environment variables are required.
4. Click **Deploy**.

The homepage uses the green design. `/green` and `/blue` open each colour version. Vercel deployments use Vercel's access settings; the private ChatGPT Sites login is not part of this source.

## Local preview

Run `python3 -m http.server 4173 --directory dist`, then open `http://localhost:4173`. Use `/blue.html` or `/green.html` when using this simple local server.

## Files

- `dist/index.html`: green homepage
- `dist/green.html` and `dist/blue.html`: matching colour variants
- `dist/assets/glass.css` and `dist/assets/glass.js`: shared glass styling and animation
- `.openai/hosting.json`: existing ChatGPT Sites identity; not used by Vercel

Fonts and the illustrative worship image load from external providers. The worship flyer is included locally. Content sources are explained at the bottom of each page. The service schedule comes from the supplied worship flyer. Lagos contact numbers and the start time for Lagos Power Night still need to be supplied.
