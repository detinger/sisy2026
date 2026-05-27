# SISY 2026 Website

This folder contains the website for the **IEEE 24th International Symposium on Intelligent Systems and Informatics**, September 23-25, 2026, Pula, Croatia.

The site is made from simple HTML, CSS, JavaScript, and images. There is no build step, no installation, and no special software required to publish it.

## What Is In This Folder

```
/
├── index.html             # Home page
├── program/index.html     # Program page
├── venue/index.html       # Venue / Pula page
├── submit/index.html      # Submission page
├── contact/index.html     # Committee / contact page
├── styles.css             # Visual design for every page
├── script.js              # Small interactive behavior
├── images/                # Photos used by the site
├── assets/                # Logos and supporting graphics
├── favicon.svg            # Browser tab icon
├── og-image.svg           # Social sharing preview image
└── 404.html               # Page shown for broken links
```

## How To Preview The Site

The easiest way is to open `index.html` in a browser.

For a more accurate preview, especially before publishing, ask a technical helper to run a small local web server from this folder:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How To Publish The Site

These instructions are for the person who receives the website files and uploads them to an existing university, conference, or hosting server.

1. Open the hosting file manager or FTP program.
2. Find the public website folder. It is often named `public_html`, `www`, `htdocs`, or similar.
3. Upload the contents of this folder, not the parent folder itself.
4. Make sure `index.html`, `styles.css`, `script.js`, `images/`, `assets/`, and the page folders are all uploaded together.
5. Open the website address in a browser.
6. Click through the menu: Home, Program, Pula, Submit, and Committee.

Important: keep the folder structure exactly as it is. For example, `program/index.html` should stay inside the `program` folder, and speaker photos should stay inside `images`.

## What To Send To The Server Administrator

Send the whole `sisy2026` folder as a ZIP file, or send all files and folders inside it.

The administrator should place the contents of the folder into the web server directory where the SISY 2026 website should appear. The file `index.html` must be directly inside that web directory.

## Updating Website Text

Most content can be changed by editing the HTML files:

- `index.html` for the home page
- `program/index.html` for keynotes, tracks, and program information
- `venue/index.html` for venue and travel information
- `submit/index.html` for submission and registration information
- `contact/index.html` for committees and contacts

After editing, save the file, preview the site, and then upload the changed file to the server.

## Updating Images

Images are stored in the `images` folder.

When replacing an image:

1. Use the same file name if possible.
2. Keep the image in the `images` folder.
3. Refresh the browser after uploading. If the old image still appears, clear the browser cache or open the site in a private window.

## Final Check Before Sharing

Before sending the website link publicly:

1. Open the home page.
2. Test every top navigation link.
3. Test the submission link.
4. Test the keynote abstract PDF links.
5. Check the site on a phone-sized screen.
6. Confirm that all photos are visible.
