# Auto Tech Mechanical Services – Static Site

This is a simple, static one-page website for **AUTO TECH MECHANICAL SERVICES LIMITED**, built to mirror the structure and content of the original Netlify site (`https://auto-tech-mechanical.netlify.app/`).

## Stack

- Plain HTML (`index.html`)
- CSS only (`styles.css`)
- No build tools or JavaScript required

## Project Structure

- `index.html` – main single-page layout (hero, services, about, contact)
- `styles.css` – all layout and visual styling
- `README.md` – this file

## How to Run Locally

You can open the site directly in a browser:

1. Open the project folder: `e:\Intern\Projects\Auto Tech Mechanical Services`
2. Double-click `index.html` to open it in your browser

For a better experience (especially with routing or assets) you can use a simple static server such as the VS Code/Cursor Live Server extension or `npx serve`:

```bash
cd "e:\Intern\Projects\Auto Tech Mechanical Services"
npx serve .
```

Then open the URL shown in the terminal (usually `http://localhost:3000`).

## Deploying to Netlify

1. Create a new site in Netlify
2. Choose **Deploy without Git** (or connect a repo if you add Git later)
3. Drag and drop the project folder, or set the publish directory to the folder that contains `index.html`
4. No build command is required (static site)

